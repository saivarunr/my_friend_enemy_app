start the minikube cluster with 

minikube start

create an object with

kubectl create -f file.yaml

view pods with 

kubectl get pod

view deployments with

kubectl get deployment


view services with

kubectl get service

enter a pod with

kubectl exec -ti <pod-name> -c <container-name> bash

update an object with

kubectl apply -f file.yaml