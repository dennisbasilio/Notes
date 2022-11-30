Used for test/local cluster setup
* Master and Node processes run on one machine
* Docker pre-installed
* Has kubectl as dependency (no separate installation)

Installing Minikube with homebrew
``` shell
brew install minikube
```

Starting Minikube (Docker is preferred)
```shell
minikube start --driver docker
```
Check Minikube status
```shell
minikube status
```
