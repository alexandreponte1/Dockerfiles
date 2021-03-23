kubectl apply -f pod-nginx.yml

kubectl apply -f svc-nginx.yml 

kubectl get svc

kubectl get nodes -o wide

curl 192.168.99.100:30000

minikube service --url <service-name>