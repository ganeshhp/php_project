# php_project
php sample project
Demo project for Docker-Compose

For deployment of application services to Kubernetes cluster.

1) run the command,

$ kubectl create namespace php-project

2) change the node name in volume.yaml file for node affinity as per the cluster worker node name.

3) The volume.yaml, deployment.yaml and service.yaml files are to be executed in the same order as mentioned. 

$ kubectl create -f volume.yaml

$ kubectl create -f deployment.yaml

$ kubectl create -f service.yaml


