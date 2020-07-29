# ckad-notes


# Imperative commands


kubectl run nginx-pod --image nginx:alpine

kubectl run redis --image redis:alpine --labels tier=db

kubectl expose pod redis --port=6379 --name redis-service

kubectl expose pod redis --type=clusterip --port=6379 --name redis-service

kubectl create deployment webapp --image kodekloud/webapp-color
kubectl scale deployment webapp --replicas=3

kubectl run custom-nginx --image=nginx --port=8080

