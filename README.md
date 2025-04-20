# Kubernetes config repo


## Secrets 
Apply necessary secrets before applying the resources like the Docker registry secret for camel-k named `registry-secret`

## Install ArgoCD ApplicationSet
Change to cluster with ArgoCD installation to the argocd namespace. Apply the ApplicationSet.

```
kubectl apply -f  application-set.yaml
```

## List ApplicationSet's
Change to cluster with ArgoCD installation to the argocd namespace.

```
kubectl get applicationset
```

## Delete ApplicationSet
Change to cluster with ArgoCD installation to the argocd namespace.

```
kubectl delete applicationset <name>
```
