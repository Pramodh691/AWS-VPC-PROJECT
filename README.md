# AWS VPC Project

## 📌 Project Overview
This project demonstrates the creation and configuration of an AWS Virtual Private Cloud (VPC) with public and private subnets to securely host cloud resources.

## 🛠️ Services Used
- AWS VPC
- EC2
- Subnets
- Route Tables
- Internet Gateway
- Security Groups
- Key Pairs

## 🏗️ Architecture
- Custom VPC
- Public Subnet with EC2
- Private Subnet
- Internet Gateway
- Route Tables for traffic control

## 🔐 Security
- SSH access restricted using Security Groups
- Private subnet resources are not publicly accessible

## 🚀 Outcome
- Successfully launched EC2 instances
- Configured public & private networking
- Understood real-world VPC design

## 👤 Author
**Pramodh S**  
Cloud & DevOps Enthusiast




# AWS VPC Project

## 📌 Project Overview

This project demonstrates the design and implementation of a secure and scalable **AWS Virtual Private Cloud (VPC)** architecture. The goal of this project is to understand real‑world cloud networking concepts by creating isolated networks, controlling traffic flow, and securely deploying compute resources.

This project is suitable for **Cloud Engineer / DevOps / AWS Fresher roles** and reflects hands‑on experience with AWS core networking services.

---

## 🛠️ AWS Services Used

* **Amazon VPC** – Custom virtual network
* **EC2** – Compute instances
* **Subnets** – Public and Private subnets
* **Internet Gateway (IGW)** – Internet access for public subnet
* **Route Tables** – Traffic routing rules
* **Security Groups** – Network‑level security
* **Key Pairs** – Secure SSH access

---

## 🏗️ Architecture Design

The architecture follows a standard real‑world AWS networking model:

* Created a **custom VPC** with a private IP address range
* Configured **Public Subnet** for internet‑facing resources
* Configured **Private Subnet** for internal resources
* Attached an **Internet Gateway** to the VPC
* Associated route tables to control inbound and outbound traffic
* Launched EC2 instance inside the public subnet

This setup ensures **network isolation, security, and controlled access**.

---

## 🔐 Security Implementation

* SSH access restricted using **Security Groups**
* Only required ports were opened (e.g., port 22 for SSH)
* Private subnet resources are not directly accessible from the internet
* Key Pair authentication used instead of passwords

---

## 🚀 Project Workflow

1. Created a custom VPC
2. Created public and private subnets
3. Configured and attached Internet Gateway
4. Created route tables and subnet associations
5. Launched EC2 instance in public subnet
6. Verified connectivity and access rules

---

## 📈 Outcome & Learning

* Gained hands‑on experience with AWS VPC networking
* Understood real‑world cloud network design
* Learned traffic flow using route tables and gateways
* Implemented basic cloud security best practices

---

## 📂 Repository Structure

```
AWS-VPC-PROJECT/
│
├── README.md
├── documentation/
│   └── vpc-project-summary.txt
├── screenshots/ 
└── architecture/  
```

---

## 👤 Author

**Pramodh S**
Cloud & DevOps Enthusiast


