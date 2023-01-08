# Curso Kubernetes

Curso sobre Kubernetes

1. Introducción a Kubernetes
    * [Implantación de aplicaciones web en contenedores](modulo1/implantacion-aplic-web.md)
    * [Docker](modulo1/docker.md)
    * [Orquestadores de contenedores](modulo1/orquestadores.md)
    * [El proyecto Kubernetes](modulo1/proyecto-kubernetes.md)
    * [Arquitectura básica de Kubernetes](modulo1/arquitectura.md)
1. Instalación de Kubernetes
    * [Alternativas para instalación simple de k8s](modulo2/alternativas.md)
    * [Introducción a la instalación de minikube](modulo2/instalacion-minikube.md)
    * [Instalación de minikube en linux + KVM](modulo2/instalacion-minikube-linux.md)
    * [Instalación y configuración de kubectl en linux](modulo2/instalacion-kubectl-linux.md)
    * [Despliegues de aplicaciones en Kubernetes](modulo2/despliegues-k8s.md)
        * [Actividad 2.1: Instalación de minikube y kubectl (OBLIGATORIA)](modulo2/actividad1.md)
1. Contenedores en Kubernetes: Pods
    * [Pod](modulo3/pods.md)
    * [Describiendo un Pod](modulo3/describiendo_pod.md)
	* [Gestionando los Pods](modulo3/gestionando_pod.md)
        * [Actividad 3.1: Trabajando con Pods (OBLIGATORIA)](modulo3/actividad1.md)
        * [Actividad 3.2: Trabajando con un Pod multicontenedor (VOLUNTARIA)](modulo3/actividad2.md)
1. Tolerancia y escalabilidad: ReplicaSets
	* [ReplicaSet](modulo4/replicaset.md)
	* [Describiendo un ReplicaSet](modulo4/describiendo_replicaset.md)
    * [Gestionando los ReplicaSet](modulo4/gestionando_replicaset.md)
        * [Actividad 4.1: Trabajando con ReplicaSet (OBLIGATORIA)](modulo4/actividad1.md)
1. Despliegues
    * [Deployment](modulo5/deployment.md)
    * [Describiendo un Deployment](modulo5/describiendo_deployment.md)
    * [Gestión básica de un Deployment](modulo5/gestionando_deployment.md)
    * [Actualización y desactualización de un Deployment](modulo5/actualizacion_deployment.md)
        * [Actividad 5.1: Trabajando con Deployments (OBLIGATORIA)](modulo5/actividad1.md)
        * [Actividad 5.2: Actualización y desactualización de nuestra aplicación (OBLIGATORIA)](modulo5/actividad2.md)
        * [Actividad 5.3: Despliegue de la aplicación GuestBook (OBLIGATORIA)](modulo5/actividad3.md)
1. Acceso a las aplicaciones
    * [Services. Tipos de Services](modulo6/services.md)
    * [Describiendo Services](modulo6/describiendo_services.md)
    * [Gestionando los Services](modulo6/gestionando_services.md)
    * [Servicio DNS en Kubernetes](modulo6/dns.md)
    * [Ingress Controller](modulo6/ingress.md)
    * [Ejemplo completo: Desplegando y accediendo a la aplicación Temperaturas](modulo6/temperaturas.md)
        * [Actividad 6.1: Acceso de la aplicación GuestBook (OBLIGATORIA)](modulo6/actividad1.md)
        * [Actividad 6.2: Despliegue y acceso de la Aplicación Lets-Chat (VOLUNTARIA)](modulo6/actividad2.md)
1. Despliegues parametrizados
    * [Variables de entorno](modulo7/variables_entorno.md)
	* [ConfigMaps](modulo7/configmaps.md)
	* [Secrets](modulo7/secrets.md)
    * [Ejemplo completo: Despliegue y acceso a Wordpress + MariaDB](modulo7/wordpress.md)
        * [Actividad 7.1: Configurando nuestra aplicación Temperaturas (OBLIGATORIA)](modulo7/actividad1.md)
        * [Actividad 7.2: Despliegue y acceso de la aplicación Nextcloud (VOLUNTARIA)](modulo7/actividad2.md)
1. Almacenamiento en Kubernetes
    * [Consideraciones sobre el almacenamiento](modulo8/consideraciones.md)
    * [Volúmenes en Kubernetes](modulo8/volumenes.md)
    * [Aprovisionamiento de volúmenes](modulo8/aprovisionamiento.md)
    * [Solicitud de volúmenes](modulo8/solicitud.md)
    * [Uso de volúmenes](modulo8/uso.md)
    * [Ejemplo 1: Gestión estática de volúmenes](modulo8/ejemplo1.md)
    * [Ejemplo 2: Gestión dinámica de volúmenes](modulo8/ejemplo2.md)
    * [Ejemplo 3: Wordpress con almacenamiento persistente](modulo8/wordpress.md)
        * [Actividad 8.1: Desplegando un servidor web persistente (OBLIGATORIA)](modulo8/actividad1.md)
        * [Actividad 8.2: Haciendo persistente la aplicación GuestBook (OBLIGATORIA)](modulo8/actividad2.md)
        * [Actividad 8.3: Haciendo persistente la aplicación Nextcloud (VOLUNTARIA)](modulo8/actividad3.md)
1. Otras cargas de trabajo
    * [¿Podemos usar un despliegue para todo?](modulo9/otras_cargas.md)
    * [StatefulSets](modulo9/statefulsets.md)
	* [Ejemplo: Despliegue de un cluster de MySQL](modulo9/ejemplo2.md)
	* [DaemonSets](modulo9/daemonsets.md)
	* [Jobs y CronJobs](modulo9/jobs.md)
        * [Actividad 9.1: Creando un cluster de MySQL (VOLUNTARIA)](modulo9/actividad1.md)
1. Instalación de aplicaciones en Kubernetes con Helm
    * [Despliegue de aplicaciones con Helm](modulo10/helm.md   )
    * [Instalación de Helm](modulo10/instalacion.md)
    * [Gestión de charts y despliegue de aplicaciones](modulo10/ejemplo.md)
        * [Actividad 10.1: Instalación de un CMS con Helm (OBLIGATORIA)](modulo10/actividad1.md)

