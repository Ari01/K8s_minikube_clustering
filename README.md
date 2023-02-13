# K8s_minikube_clustering

Sets up a cluster with minikube. Services running in docker containers are :
* Kubernetes dashboard on port 8001
* NGINX on port 80
* FTPS server on port 20, 21
* Worpress on port 5050
* Grafana on port 3000
* Influxdb on port 8086
* Mysql on port 3306

## Prerequesites
* make sure you have sudo permissions on your device
* make sure localhost is available

## Usage
``` bash
sh setup.sh
```
