

First we need a Namespace:

kubectl create namespace rocketchat


kubectl apply -f ingress.yml 
kubectl apply -f rocket.chat-deployment.yml 

Variant A: with local Claim


Variant B: with PersistentVolumeClaim
Via NFS Volume