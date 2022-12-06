BUILD
kubectl apply -f manifest.yaml
DELETE
kubectl delete deployment nginx
Pod
kubectl port-forward nginx 90:8080
ReplicaSet
kubectl port-forward rs/nginx 90:8080
Deployment
kubectl port-forward deployment/nginx 90:8080