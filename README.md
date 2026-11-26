# project-school
minikube start
minikube status
kubectl get nodes
kubectl create deployment nginx-deployment --image=nginx --replicas=2
kubectl get deployments
kubectl get pods
kubectl get pods -w
kubectl port-forward deployment/nginx-deployment 8080:80
kubectl scale deployment nginx-deployment --replicas=5
kubectl get pods
kubectl get deployments
kubectl scale deployment nginx-deployment --replicas=2
kubectl get pods
kubectl describe deployment nginx-deployment
kubectl delete deployment nginx-deployment
minikube stop
