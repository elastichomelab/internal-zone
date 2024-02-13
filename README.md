# internal-zone

kubernetes

``` bash
minikube config set memory 4096
minikube confit set cpus 2
```

``` bash
minikube start -n 3
```

``` bash
minikube addons enable metrics-server
```


# nfs-provider

``` bash
helm repo add nfs-subdir-external-provisioner https://kubernetes-sigs.github.io/nfs-subdir-external-provisioner/
```


# helm values use

``` bash
helm show values jenkins/jenkins > jenkins_values.yaml 
```