# Deployment

Build an monitoring environment: <br/>

```
#   Important!
#   Create namespace - argocd
#   in your terminal

kubectl create namespace argocd
kubectl get namespace
kubectl apply -f install.yaml

```
Or: <br/>

kubectl create namespace argocd
kubectl apply -n argocd -f https://raw.githubusercontent.com/argoproj/argo-cd/stable/manifests/install.yaml

```
documentation here: <br/>

# Wait resources get ready.



```
