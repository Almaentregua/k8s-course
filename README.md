# k8s-course

# Material
## Video: https://www.youtube.com/watch?v=d6WC5n9G_sM&
## Documentation: https://kubernetes.io/docs/reference/kubernetes-api/workload-resources/

# Some kubectl commands

## kubectl version --client
## kubectl get nodes
## kubectl get pods
## kubectl get namespaces
## kubectl get services
## kubectl get deployments
## kubectl get pods
## kubectl get pods -o wide
## kubectl describe deployments
## kubectl describe pod 
## kubectl describe pod nginx-deployment-55888b446c-x2sqv
## kubectl cluster-info
## kubectl delete pod nginx
## kubectl delete deployment nginx-deployment
## kubectl delete all --all
## kubectl apply -f deployment.yaml -f service.yaml
## kubectl delete -f deployment.yaml -f service.yaml
## kubectl run nginx --image=nginx
## kubectl create deployment nginx-deployment --image=nginx
## kubectl expose deployment nginx-deployment --port=8080 -target-port=80 #crear service
## kubectl scale deployment nginx-deployment --replicas=3

# Some minikube commands
## minikube start --driver=virtualbox
## minikube version
## minikube help
## minikube status
## minikube ip
## minikube ssh
## minikube service k8s-web-to-nginx


# Some docker commands

## docker push juanmamartin/k8s-web-to-nginx
## docker build . -t juanmamartin/k8s-web-to-nginx 