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

1. Contenedores en Kubernetes: Pods
    * [Pod](modulo3/pods.md)
    * [Describiendo un Pod](modulo3/describiendo_pod.md)
	* [Gestionando los Pods](modulo3/gestionando_pod.md)

1. Tolerancia y escalabilidad: ReplicaSets
	* [ReplicaSet](modulo4/replicaset.md)
	* [Describiendo un ReplicaSet](modulo4/describiendo_replicaset.md)
    * [Gestionando los ReplicaSet](modulo4/gestionando_replicaset.md)

1. Despliegues
    * [Deployment](modulo5/deployment.md)
    * [Describiendo un Deployment](modulo5/describiendo_deployment.md)
    * [Gestión básica de un Deployment](modulo5/gestionando_deployment.md)
    * [Actualización y desactualización de un Deployment](modulo5/actualizacion_deployment.md)

1. Acceso a las aplicaciones
    * [Services. Tipos de Services](modulo6/services.md)
    * [Describiendo Services](modulo6/describiendo_services.md)
    * [Gestionando los Services](modulo6/gestionando_services.md)
    * [Servicio DNS en Kubernetes](modulo6/dns.md)
    * [Ingress Controller](modulo6/ingress.md)
    * [Ejemplo completo: Desplegando y accediendo a la aplicación Temperaturas](modulo6/temperaturas.md)

1. Despliegues parametrizados
    * [Variables de entorno](modulo7/variables_entorno.md)
	* [ConfigMaps](modulo7/configmaps.md)
	* [Secrets](modulo7/secrets.md)
    * [Ejemplo completo: Despliegue y acceso a Wordpress + MariaDB](modulo7/wordpress.md)

1. Almacenamiento en Kubernetes
    * [Consideraciones sobre el almacenamiento](modulo8/consideraciones.md)
    * [Volúmenes en Kubernetes](modulo8/volumenes.md)
    * [Aprovisionamiento de volúmenes](modulo8/aprovisionamiento.md)
    * [Solicitud de volúmenes](modulo8/solicitud.md)
    * [Uso de volúmenes](modulo8/uso.md)
    * [Ejemplo 1: Gestión estática de volúmenes](modulo8/ejemplo1.md)
    * [Ejemplo 2: Gestión dinámica de volúmenes](modulo8/ejemplo2.md)
    * [Ejemplo 3: Wordpress con almacenamiento persistente](modulo8/wordpress.md)

1. Otras cargas de trabajo
    * [¿Podemos usar un despliegue para todo?](modulo9/otras_cargas.md)
    * [StatefulSets](modulo9/statefulsets.md)
	* [Ejemplo: Despliegue de un cluster de MySQL](modulo9/ejemplo2.md)
	* [DaemonSets](modulo9/daemonsets.md)
	* [Jobs y CronJobs](modulo9/jobs.md)

1. Instalación de aplicaciones en Kubernetes con Helm
    * [Despliegue de aplicaciones con Helm](modulo10/helm.md   )
    * [Instalación de Helm](modulo10/instalacion.md)
    * [Gestión de charts y despliegue de aplicaciones](modulo10/ejemplo.md)
