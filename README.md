# Terraform EKS Project

This project provisions a complete Amazon EKS (Elastic Kubernetes Service) cluster using **Terraform**.

---

## 📌 **Project Summary**
- **Infrastructure as Code (IaC)** using Terraform
- Creates a VPC with 3 public subnets in different AZs (for high availability)
- Adds an Internet Gateway + Route Tables
- Deploys an EKS cluster (control plane managed by AWS)
- Configures an EKS managed node group (worker nodes)

---

## 🚀 **What I used**
- **Terraform:** to write and apply infrastructure code
- **AWS CLI:** to update kubeconfig for kubectl access
- **kubectl:** to interact with the Kubernetes cluster
- **VS Code:** for writing Terraform files and managing Git

---

