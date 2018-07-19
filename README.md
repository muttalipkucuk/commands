# Command

| Program                   | Command   |
| ------------------------- |:---------:|
| [General](#general)       |           |
| [Git](#git)               | `git`     |
| [Kubernetes](#kubernetes) | `kubectl` |
| [sbt](#sbt)               | `sbt`     |


## General

```
cat file1.txt
curl www.example.com
exit
export -p
export NAME_VARIABLE=value

```


## Git

```
git clone
git add . -p
git commit -m "Some message"
git push
git pull
git fetch
```


## Kubernetes

```
kubectl version
kubectl cluster-info
kubectl get
kubectl get pods
kubectl get pods -l label-name
kubectl get deployments
kubectl get nodes
kubectl get services
kubectl get services -l label-name
kubectl proxy
kubectl run node-name --image=link-to-image.com --port=8080
kubectl describe
kubectl logs
kubectl exec 

```


## sbt

```
sbt clean
sbt compile
sbt run 9060
sbt test
sbt testOnly com.google.package.x.*
```

