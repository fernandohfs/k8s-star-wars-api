# k8s-star-wars-api

## Kubernetes via .yml files

```sh
kubectl apply -f star-wars-api-deployment.yml
kubectl apply -f star-wars-api-service.yml
kubectl get pods
kubectl port-forward nome-verdadeiro-do-pod 5555
```
## Obtendo resposta do health check

```sh
curl http://localhost:5555/health/check

{ "message": "pong :)" }
```