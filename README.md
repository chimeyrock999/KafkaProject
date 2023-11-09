## Part 1: Introduction

### Prerequisite
To start with this project, you should have:
- A Kubernetes cluster & 

## Part 2: Setup ArgoCD
> Follow these instruction https://argo-cd.readthedocs.io/en/stable/getting_started/
- Step 1: Install ArgoCD
```shell
kubectl create namespace argocd
kubectl apply -n argocd -f https://raw.githubusercontent.com/argoproj/argo-cd/stable/manifests/install.yaml
```
- 

