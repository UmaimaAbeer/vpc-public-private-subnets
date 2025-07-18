# VPC with Public and Private Subnets

This project demonstrates how to create a custom Virtual Private Cloud (VPC) in AWS with properly segmented public and private subnets. It is a foundational component of cloud architecture and security best practices.

## 📌 Key Components

- **Custom VPC** with a defined CIDR block (`10.0.0.0/16`)
- **Public Subnet** (`10.0.1.0/24`) with internet access
- **Private Subnet** (`10.0.2.0/24`) without direct internet access
- **Internet Gateway** for public subnet routing
- **Route Tables** for managing traffic flow
- **Security Group** allowing only specific traffic (e.g., SSH for public subnet)
- **Network ACLs** (optional) for subnet-level filtering

## 🔧 Tools Used

- AWS Management Console
- VPC Wizard (Manual configuration)
- CIDR Planning
- AWS Region: Asia Pacific (Mumbai)

## ✅ Outcome

By the end of this project:
- A secure network environment was created with isolated private resources.
- Public-facing instances can interact securely with the internet.
- The foundation for future scalable and secure cloud deployments was established.

## 📂 Files Included

- `vpc-public-private-subnets.pdf` – Full step-by-step documentation
- `vpc-public-private-subnets.json` – Project summary metadata in JSON
- `project 4.png` – Visual diagram of the architecture

![Uploading image.png…]()




---

**Status:** ✅ Completed  
**Author:** Syeda Umaima Abeer  
**Date:** 18 July 2025
