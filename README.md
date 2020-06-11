# k8s

```
gcloud container clusters create cluster-1 --zone us-central1-a

gcloud container clusters get-credentials cluster-1 --zone us-central1-a

kubectl get nodes

kubectl apply -f deployment.yaml

kubectl apply -f service.yaml

```

**Note** 
1. Selector for service should be the label app given in the deployment.yaml
2. name in deployment, service are basically to identify it.
