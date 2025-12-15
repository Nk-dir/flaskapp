# Terraform Provisioners – EC2 Deployment using IaC

In this project, I created and configured cloud infrastructure using **Terraform (Infrastructure as Code)**.

## ✅ What I Did

- Created an **EC2 instance** using Terraform
- Assigned a **public IP address** to the EC2 instance
- Configured **security group rules** to allow SSH access
- Connected to the EC2 instance using **SSH**
- Used **Terraform provisioners** to automate deployment tasks

## ⚙️ Provisioning & Deployment

- Used **file provisioner** to copy required files/scripts to the EC2 instance
- Used **remote-exec provisioner** to:
  - Update the server
  - Install required packages
  - Deploy and start the application/service
- Used **local-exec provisioner** for local command execution during provisioning

## 🛠️ Tools & Technologies

- Terraform
- AWS EC2
- SSH
- Terraform Provisioners (local-exec, remote-exec, file)
