# ckad-notes


# Imperative commands
The imperative approach involves using any of the verb based commands, here are some them:

- kubectl run
- kubectl create
- kubectl expose
- kubectl delete
- kubectl edit

- kubectl run pod-httpd --image=httpd --labels="app=apache_webserver" --restart=Never
- kubectl run nginx-pod --image nginx:alpine
- kubectl run redis --image redis:alpine --labels tier=db
- kubectl run custom-nginx --image=nginx --port=8080


kubectl expose pod redis --port=6379 --name redis-service

kubectl expose pod redis --type=clusterip --port=6379 --name redis-service

kubectl create deployment webapp --image kodekloud/webapp-color

kubectl scale deployment webapp --replicas=3


kubectl expose pod httpd --port=80 --name=httpd
