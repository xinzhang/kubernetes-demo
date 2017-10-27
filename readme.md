## Installation:
brew install kubectl
brew cask install minikube

## Version:
kubectl version
minikube version

## Start/Stop
minikube start --vm-driver=xhyve
minikube stop
minikube delete

## Status
kubectl get nodes
kubectl get deployments
kubectl get service
kubectl get pods

## Build
kubectl apply -f <foldername>


## Execute
minikube dashboard

minikube service <servicename>

## scale
kubectl apply -f <foldername>\hpa.yml
kubectl get hpa

minikube addons list
minikube addons enable heapster

