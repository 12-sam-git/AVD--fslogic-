# AVD--fslogic-
Azure Virtual Desktop with Active Directory Integration 

# Azure Virtual Desktop with Active Directory – Proof of Concept (POC)

## 📌 Overview
This repository contains a **Proof of Concept (POC)** for implementing **Azure Virtual Desktop (AVD)** integrated with **Active Directory Domain Services (AD DS)**.  
The POC demonstrates how to configure **Personal and Pooled Host Pools**, assign users, and manage **persistent user profiles** using **FSLogix** and **Azure File Share**.

This project is designed from a **beginner-to-intermediate Azure perspective** and follows real-world enterprise practices.

---

## 🎯 Objectives
- Deploy an Active Directory Domain Controller in Azure
- Create and configure Azure Virtual Desktop
- Implement:
  - Personal Host Pool (dedicated VM per user)
  - Pooled Host Pool (shared VM for multiple users)
- Join all session hosts to Active Directory
- Assign users to host pools
- Store user profiles centrally using FSLogix

---

## 🏗️ Architecture Overview
- Azure Virtual Network
- Windows Server (Domain Controller)
- Azure Virtual Desktop Workspace
- Personal Host Pool (1 VM)
- Pooled Host Pool (1 VM, multiple users)
- Azure Storage Account (Azure Files) for FSLogix profiles

---

## 🛠️ Technologies Used
- Microsoft Azure
- Azure Virtual Desktop (AVD)
- Windows Server 2022
- Active Directory Domain Services (AD DS)
- FSLogix
- Azure Storage Account (File Share)

---

---

## 📄 Documentation
Detailed implementation steps and explanations are available in document :  


---

## ✅ Key Features
- Domain-based authentication
- Dedicated desktops using Personal Host Pools
- Cost-effective shared desktops using Pooled Host Pools
- Persistent user profiles across sessions
- Enterprise-ready and scalable architecture

---

## 🔍 Use Cases
- Azure Virtual Desktop learning and labs
- Fresher / beginner Azure projects
- Interview demonstrations
- Internal POC or training environments

---

## 🚀 Future Enhancements
- Azure AD / Entra ID integration
- Autoscaling for host pools
- Azure Monitor and Log Analytics
- Multi-Factor Authentication (MFA)

---

## 👤 Author
**Sameeksha Y S**  
Azure | Cloud | DevOps Enthusiast

---

## 📌 Note
This project is created for **learning, demonstration, and interview preparation purposes**.



