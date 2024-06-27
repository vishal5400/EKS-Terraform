# AWS EKS Cluster with Managed Node Group and ALB Ingress Controller using Terraform

This repository contains Terraform code to create an Amazon EKS (Elastic Kubernetes Service) cluster with a managed node group and the AWS ALB (Application Load Balancer) Ingress Controller.

## Prerequisites

- Terraform
- AWS CLI configured with appropriate credentials
- kubectl
- AWS IAM Authenticator for Kubernetes
- Helm

## Setup Instructions

### 1. Clone the Repository

```sh
git clone https://github.com/yourusername/your-repo.git
cd your-repo
```
### 2. Configure Terraform Variables and apply

**Note:** After that, set up the ALB Ingress Controller. Use the eksctl.txt file and follow the steps in the file. For testing everything, use the content in the kube folder. This folder contains the deployment file, service file, and ingress file.
