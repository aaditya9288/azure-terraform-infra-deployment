# 🚀 Azure Terraform Infra + Docker Deployment

This project demonstrates end-to-end cloud infrastructure provisioning and application deployment using Terraform, Docker, and GitHub Actions.

---

## 📌 Architecture

GitHub → GitHub Actions → Terraform → Azure → VM → Docker → Nginx → Internet

---

## ⚙️ Tech Stack

- Cloud: Microsoft Azure  
- IaC: Terraform  
- Containerization: Docker  
- CI/CD: GitHub Actions  
- OS: Ubuntu  

---

## 🔧 What I Built

- Provisioned Azure infrastructure using Terraform (VM, VNet, Subnet, NSG, Public IP)  
- Deployed Nginx using Docker inside an Azure Virtual Machine  
- Configured network security rules for HTTP (80) and SSH (22)  
- Automated VM setup using cloud-init scripts  
- Implemented CI/CD pipeline using GitHub Actions  

---

## 🐛 Challenges Faced

- SSH connection timeout due to NSG misconfiguration  
- Application not accessible due to blocked ports  
- Docker permission issues inside VM  
- CI/CD pipeline stuck due to missing variables  

---

## 💡 Key Learnings

- Infrastructure as Code simplifies cloud provisioning  
- Debugging real-world issues is critical in DevOps  
- CI/CD pipelines help automate and validate deployments  

---

## 🚀 How to Use

```bash
terraform init
terraform plan
terraform apply

   
   
