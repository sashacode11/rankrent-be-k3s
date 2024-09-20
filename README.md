# rankrent-be-k3s

```
kubectl get pods
kubectl delete pod <pod-name>
kubectl create secret generic rankrent-secrets --from-env-file=.env
kubectl apply -f deployment.yml
kubectl port-forward deployment/rankrent-be 3001:3001

```
