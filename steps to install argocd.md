
- Step1
create argocd ns
``` bash
kubectl create ns argocd
```
- Step2
install argodcd by using 
``` bash
kubectl apply -n argocd -f https://raw.githubusercontent.com/argoproj/argo-cd/stable/manifests/install.yaml
```
