# Terraform Installation

`https://developer.hashicorp.com/terraform/tutorials/aws-get-started/install-cli `

# AWSCLI Installation

`https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html` 


## Commands

```
aws eks update-kubeconfig --region us-east-1 --name Tetris-EKS-Cluster
```

```
kubectl apply -n argocd -f https://raw.githubusercontent.com/argoproj/argo-cd/v2.4.7/manifests/install.yaml
```

```
kubectl patch svc argocd-server -n argocd -p '{"spec": {"type": "LoadBalancer"}}`
```

## ArgoCD Initial PW

` https://stackoverflow.com/questions/68297354/what-is-the-default-password-of-argocd`