# Index

| Tool                          | Command   |
| ----------------------------- |:---------:|
| [Shell](#shell)               |           |
| [Google Cloud](#googlecloud)  | `...`     |
| [Git](#git)                   | `git`     |
| [Kubernetes](#kubernetes)     | `kubectl` |
| [Maven](#maven)               | `mvn`     |
| [npm](#npm)                   | `npm`     |
| [sbt](#sbt)                   | `sbt`     |
| [...](#...)                   | `...`     |


## Shell

```
cat file1.txt
curl www.example.com
exit
export -p
export NAME_VARIABLE=value
nano .bash_profile
echo -n 'SomePassword123' | base64
printenv
grep -Hrn 'search_term' /search-folder
```


## GoogleCloud

```
gcloud container clusters get-credentials <cluster-name> --zone <zone> --project <project>
```


## Git

```
git config --global user.name "muttalipkucuk"
git config --global user.email muttalip@example.com
git init
git clone /path/to/repository
git clone username@host:/path/to/repository
git add *
git add <file-name>
git add . -p
git commit -m "Some message"
git push
git push origin master
git push origin <branch-name>
git push origin :<branchname>
git status
git remote add origin <server>
git remote -v
git checkout <branchname>
git checkout -b <branch-name>
git checkout -- <filename>
git branch
git branch -d <branch-name>
git pull
git merge <branch-name>
git fetch
git fetch origin
git diff
git diff <source-branch> <target-branch>
git tag 1.0.0 <commit-ID>
git log
git reset --hard origin/master
git stash save "some message"
git stash list
git stash apply stash@{n}
git diff --staged (or git diff --cached)
git checkout HEAD -- my-file.txt
```

Merge master into (existing) branch `myBranch`:
```
git checkout myBranch
git pull origin master
```

## Kubernetes

```
kubectl [command] [TYPE] [NAME] [flags]
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
kubectl port-forward <service-name> <local-port> <pod-port>
kubectl create -f ./secret.yaml
kubectl delete secret name-of-secret
kubectl config use-context name-of-cluster
kubectl config get-contexts

kubectl describe node the-name-of-the-node
```


## Maven

```
mvn --version
mvn validate
mvn compile
mvn test
mvn package
mvn integration-test
mvn verify
mvn install
mvn install -P <build-profile>
mvn deploy
mvn clean
mvn site
```


## npm

```
npm version
npm install
npm update
```


## sbt

```
sbt clean
sbt compile
sbt run 9060
sbt test
sbt testOnly com.google.package.x.*
sbt reload
sbt update
```


## brew

```
/usr/local/Cellar/cassandra (Location Cassandra is installed using Brew)
```


## ...

```
...
```

### Make script executable
```
chmod +x script.sh
```
