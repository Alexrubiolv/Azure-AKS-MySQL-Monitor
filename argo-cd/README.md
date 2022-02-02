# Deployment

Build an monitoring environment: <br/>

```
#   Important!
#   Create namespace - argocd
#   in your terminal <br/>

kubectl create namespace argocd
kubectl get namespace
kubectl apply -f install.yaml

```
Or: 

kubectl create namespace argocd

kubectl apply -n argocd -f https://raw.githubusercontent.com/argoproj/argo-cd/stable/manifests/install.yaml

```


```
# Documentation here: https://argo-cd.readthedocs.io/en/stable/ click the + New App button

```

# Creating Apps Via UI

click the + New App button 
Click edit as YAML
Copy app.yaml from the folder
Click Create

# Wait resources get ready.



```
