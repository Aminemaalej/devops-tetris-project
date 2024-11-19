# 🚀 DevOps Project - AWS EKS, Terraform, Jenkins, ArgoCD
[![LinkedIn](https://img.shields.io/badge/Connect%20with%20me%20on-LinkedIn-blue.svg)](https://www.linkedin.com/in/amine-maalej/)

[![Youtube](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@CloudTech_with_Amine)


![](slides/slide0.png)


## 🌟 Overview
In this step-by-step guide, we take you through an exciting DevOps project where we deploy a fully functional Tetris game application on an AWS EKS (Elastic Kubernetes Service) cluster.
- **Use Terraform for creating and managing AWS infrastructure as code**
- **Set up Jenkins for a powerful CI/CD pipeline**
- **Implement ArgoCD for seamless GitOps deployment to Kubernetes**

## 📝 Comprehensive Guide
For a detailed guide, please refer to the [Youtube video](https://www.youtube.com/watch?v=QuxDc-u-jrQ).

## ✅ Slides

Slide 1            | Slide 2         | Slide 3       
:------------------------:|:-----------------------:|:----------------------:
![](slides/slide1.png)  | ![](slides/slide2.png) | ![](slides/slide3.png)

## 💻 Commands

```
aws eks update-kubeconfig --region us-east-1 --name Tetris-EKS-Cluster
```

```
kubectl apply -n argocd -f https://raw.githubusercontent.com/argoproj/argo-cd/v2.4.7/manifests/install.yaml
```

```
kubectl patch svc argocd-server -n argocd -p '{"spec": {"type": "LoadBalancer"}}`
```

## 🔗 Links

### Terraform Installation

```
https://developer.hashicorp.com/terraform/tutorials/aws-get-started/install-cli
```
### AWSCLI Installation

```
https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html` 
```

### ArgoCD Initial Password

```
https://stackoverflow.com/questions/68297354/what-is-the-default-password-of-argocd
```

Happy learning 📚