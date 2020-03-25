## Install Kubectl in windows
* Install using scoop: scoop install kubectl
* [Refer documentation](https://kubernetes.io/docs/tasks/tools/install-kubectl/#install-kubectl-on-windows)
* Check version: kubectl version

## Install Kubectl in windows
* Install chocolatey. Refer cerebro for steps
* choco install minikube
* choco install kubernetes-cli
* If you have previously installed minikube, and run: minikube start
* And this command returns an error: machine does not exist
* You need to clear minikube’s local state: minikube delete
* [Installation documentation](https://kubernetes.io/docs/tasks/tools/install-minikube/)