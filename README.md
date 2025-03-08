# k8s_plus_django

пересборка образа  

```
docker build -t username/k8s-django-app:latest .
docker push username/k8s-django-app:latest
kubectl rollout restart deployment django-app
kubectl get pods 
kubectl port-forward svc/django-app-service 8000:80

```

 
