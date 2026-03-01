auto scaling is important that's why we need deployment.

# but we don't need to change any service code as it is previous


```
kubectl get pod
kubectl get svc
kubectl get deployment
cd voting_app_deployment

kubectl apply -f .
kubectl get svc
kubectl get deployment
kubectl get pod
kubectl get rs
kubectl get all

# get the access through web browser

kubectl get svc
kubectl get pod -o wide
kubectlt get node -o wide # get ip address and paste it in browser for accessing external users

IP Address:voting_app_port for voting
IP Address:result_app_port for showing result

kubectl get pod
kubectl get deployment

# scale the vote deployment from 1 to 5
kubectl scale deployment vote --replicas=5

kubectl get deployment
```