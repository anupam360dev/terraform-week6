# 🚀 Week 6 – Infrastructure as Code (IaC) with Terraform  
**Project Name:** terraform-week6  
**Student:** Anupam Das  
**Location:** Hyderabad  
**Cloud Provider:** AWS (Free Tier)  
**Instance Type:** t3.micro (Free-tier eligible)  
**Region:** ap-south-1 (Mumbai)  

---

## 📌 Project Objective
The goal of this project is to understand and implement **Infrastructure as Code (IaC)** using **Terraform** by deploying a virtual machine (EC2 instance) on AWS.

This project demonstrates:
- Setting up AWS IAM for Terraform  
- Configuring AWS CLI  
- Writing Terraform configuration in HCL  
- Initializing, planning, applying, and destroying infrastructure  
- Managing cloud resources using code  

---

## 📁 Project Structure
terraform-week6/
│
├── main.tf
├── terraform.lock.hcl
├── README.md
└── ec2-screenshot.png (EC2 running instance)

---

## 🛠️ Tools & Technologies Used
- **Terraform v1.x**
- **AWS IAM**
- **AWS CLI v2**
- **Amazon EC2**
- **Ubuntu/Linux Terminal**

---

# 🧩 Step-by-Step Implementation

## 1️⃣ Create IAM User for Terraform
- Created IAM user: `terraform-user`  
- Attached permissions:
  - `AmazonEC2FullAccess`
  - `AmazonVPCFullAccess`
- Generated **Access Key ID** and **Secret Key**

---

## 2️⃣ Configure AWS CLI
```bash
aws configure
