# AzureProject

Tumhare project **City Hospital Cloud Infrastructure on Microsoft Azure** ke liye ek professional README:

# 🏥 City Hospital Cloud Infrastructure on Microsoft Azure

A cloud-based hospital infrastructure project developed using **Microsoft Azure** to demonstrate secure, scalable, and reliable healthcare resource management. This project integrates networking, identity management, virtual machines, storage, backup, and disaster recovery services within Azure. 

## 🚀 Project Overview

The objective of this project is to design and deploy a complete hospital cloud infrastructure that enables:

* Secure network communication
* Role-based access control (RBAC)
* Virtualized computing resources
* Cloud storage for patient records
* Backup and disaster recovery
* Scalable cloud architecture

The solution is built using Microsoft Azure services and follows cloud security and management best practices. 

---

## 🛠️ Azure Services Used

* Resource Group
* Virtual Network (VNet)
* Subnets
* Microsoft Entra ID (Azure AD)
* Role-Based Access Control (RBAC)
* Virtual Machine (Windows Server 2022)
* Storage Account
* Blob Storage Container
* Shared Access Signature (SAS)
* Recovery Services Vault
* Backup Services

---

## 📋 Project Architecture

```text
Users
   │
   ▼
Azure AD Groups
   │
   ▼
RBAC / IAM
   │
   ▼
Hospital VNet
   │
   ▼
Department Subnets
   │
   ▼
Virtual Machine
   │
   ▼
Storage Account
   │
   ▼
Blob Container
   │
   ▼
Backup & Recovery Vault
```

---

## 🔹 Implementation Steps

### 1. Resource Group

Created **Hospital-RG** in Central India region to manage all Azure resources.

### 2. Virtual Network

Created **Hospital-VNet** with address space:

```text
10.0.0.0/16
```

### 3. Department Subnets

Configured dedicated subnets for:

* Emergency
* Outpatient
* Inpatient
* Radiology
* Pathology
* Pharmacy
* Surgery
* ICU

### 4. Identity & Access Management

Created multiple Azure AD groups and assigned RBAC permissions using:

```text
Data Factory Contributor Role
```

### 5. Virtual Machine

Deployed:

```text
ICU-VM1
Windows Server 2022
```

for hospital application workloads.

### 6. Storage Account

Created Storage Account:

```text
hospitalstorage26262
```

for storing hospital data.

### 7. Blob Container

Created:

```text
patient-records
```

container for patient information and reports.

### 8. SAS Token

Generated secure Shared Access Signature (SAS) URL for controlled access to storage resources.

### 9. Backup Configuration

Configured Recovery Services Vault:

```text
Hospital-Backup
```

to protect virtual machine data and enable disaster recovery.

---

## 🔐 Security Features

* Role-Based Access Control (RBAC)
* Secure Network Segmentation
* Azure AD Authentication
* HTTPS-only SAS Access
* Data Protection through Backup Vault
* Controlled User Permissions

---

## 🎯 Key Benefits

✅ High Availability

✅ Scalability

✅ Centralized Resource Management

✅ Secure Data Storage

✅ Disaster Recovery Support

✅ Cost-Effective Cloud Infrastructure

---

## 📷 Project Deliverables

* Azure Portal Implementation
* Architecture Design
* Configuration Screenshots
* Video Demonstration
* Documentation Report
* Cloud Deployment Walkthrough

---

## 👨‍💻 Author

**Bittu Kumar**
B.Tech Computer Science & Engineering (Cloud Computing)
Lovely Professional University

GitHub: https://github.com/CSEBittuKr/AzureProject/tree/main

---

## 📜 Conclusion

This project successfully demonstrates the deployment of a secure and scalable healthcare infrastructure using Microsoft Azure. By integrating networking, identity management, compute, storage, and backup services, the solution provides a real-world example of cloud adoption in the healthcare sector while ensuring security, reliability, and business continuity. 

Yeh README GitHub par daaloge to kaafi professional lagega aur placement/project showcase ke liye bhi achha rahega.
