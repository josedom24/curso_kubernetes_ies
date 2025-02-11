## Instalación de minikube en linux con KVM

Accedemos a
[https://minikube.sigs.k8s.io/docs/start/](https://minikube.sigs.k8s.io/docs/start/)
y seleccionamos el método que prefiramos para instalar, eligiendo
nuestro sistema operativo, arquitectura, etc.

Minikube se instala, como otras aplicaciones de Go, como un binario
enlazado estáticamente (autoconsistente), que no tiene dependencias de
nada y que tenemos que ubicar en algún directorio del PATH de nuestro
sistema. Veamos en particular la instalación directa del binario en un
sistema linux:

Paso 1: Descargamos como usuario normal y con ayuda de la aplicación
curl, la última versión del binario de minikube (en este caso para
arquitectura x86-64):

    curl -LO https://storage.googleapis.com/minikube/releases/latest/minikube-linux-amd64

Paso 2: Movemos el binario a un directorio del PATH (lo recomendable
en este caso sería /usr/local/bin/) y establecemos permisos de
ejecución. Todo esto puede hacerse con los comandos `mv` y `chmod`, o
de forma más sencilla con `install`

    sudo install minikube-linux-amd64 /usr/local/bin/minikube

Comprobamos que se ha instalado correctamente con:

    minikube version

    minikube version: v1.35.0

## Creación del clúster de k8s

El siguiente paso consiste en lanzar minikube para que cree el cluster
de Kubernetes de un solo nodo (master+worker). Minikube puede crear
este cluster en diversos sistemas de virtualización o sobre docker, lo
recomendable es visitar la página de
["drivers"](https://minikube.sigs.k8s.io/docs/drivers/) y seleccionar
el método más adecuado para nuestro sistema.

De forma general, se creará el clúster de Kubernetes a través de
minikube, mediante la instrucción:

    minikube start

Aunque de forma más concreta, especificaremos el "driver" a utilizar,
por ejemplo:

    minikube start --driver=kvm2

Esto creará de forma automática una máquina virtual o un contenedor en
el sistema escogido e instalará Kubernetes en ella. Por último, se
configura kubectl si está instalado (el cliente de línea de comandos
de k8s) para que utilice el cluster recién instalado. Podemos ver una
salida típica de la instalación del cluster a continuación:

```
😄  minikube v1.xx.0 en Debian...
...
🏄  Done! kubectl is now configured to use "minikube" cluster and "default" namespace by default
```

En la última línea de la salida podemos ver que se ha intentado
configurar apropiadamente kubectl, a pesar de que no está instalado en
el equipo, paso que haremos en el siguiente apartado.

Podemos comprobar en cualquier momento el estado de minikube con la
instrucción:

```
minikube status
minikube
type: Control Plane
host: Running
kubelet: Running
apiserver: Running
kubeconfig: Configured
```

## Parada y reinicio de minikube

Podemos parar y volver a arrancar minikube cuando sea preciso, ya que
no se trata de un clúster de k8s en producción, sino de uno instalado
en un equipo convencional. Esto se realiza mediante las instrucciones:

```
minikube stop
✋  Stopping node "minikube"  ...
🛑  1 nodes stopped.
```

```
minikube start
😄  minikube v1.xx.0 en Debian...
...
```

## Vídeo

[https://www.youtube.com/watch?v=0l_NICnY7AI](https://www.youtube.com/watch?v=0l_NICnY7AI)
