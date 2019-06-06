##Session Cluster
kubectl create -f jobmanager-service.yaml
kubectl create -f jobmanager-deployment.yaml
kubectl create -f taskmanager-deployment.yaml

kubectl delete -f jobmanager-deployment.yaml
kubectl delete -f taskmanager-deployment.yaml
kubectl delete -f jobmanager-service.yaml
