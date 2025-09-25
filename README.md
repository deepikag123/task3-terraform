# Task 3 – Terraform + Docker Project

## 📌 Project Overview
This project demonstrates how to use **Terraform** to provision a Docker container running **Nginx**.  
The Nginx web server will be accessible at **http://localhost:8080**.

---

## 🛠 Tools Used
- Terraform  
- Docker Desktop  
- Git & GitHub  

---

## 🚀 Steps to Run

1. Initialize Terraform - terraform init
2. Plan the infrastructure - terraform plan -out=tfplan
3. Apply configuration - terraform apply -auto-approve
4. Verify running container - docker ps
5. Open in browser - http://localhost:8080
   
---

##📸 Proof of Work

Screenshots of Terraform execution, Docker container, and Nginx page are available in the screenshots/ folder.

---

🧹 Cleanup

To remove the resources - terraform destroy -auto-approve
