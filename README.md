

<p align="center">
<img src="https://github.com/user-attachments/assets/a680558c-5f33-4c36-86ca-aa141706d0cb" 
</p>


# 🖥️ Active Directory: Setup in Azure

## 📌 Overview
This lab involved creating and configuring a cloud-based IT infrastructure using Microsoft Azure. I deployed a Windows Server 2022 virtual machine (DC-1) to serve as the domain controller and a Windows 10 virtual machine (Client-1) to act as a domain-joined client system.

## 🧰 Skills & Tools
- Microsoft Azure  
- Windows Server 2022 / Windows 10  
- Remote Desktop Protocol (RDP)  
- Virtual Networking / DNS Configuration  
- Command Line / PowerShell  

## ✅ What Was Done
- Created a new Azure resource group, virtual network, and subnet.
- Deployed and configured two VMs:
  - DC-1: Windows Server 2022 (Domain Controller)
  - Client-1: Windows 10 (Domain Client)
- Set static private IP on DC-1
- Modified DNS settings on Client-1 to point to DC-1
- Verified network connectivity using `ping` and `ipconfig`

## 🛠️ Tools Used
- Azure Portal  
- Windows Admin Tools  
- RDP (Remote Desktop Protocol)

## 🖼️ Screenshots  

https://github.com/user-attachments/assets/3a830ea5-b71e-4b62-b45e-dd7e5e3e6a58


## 📘 Lessons Learned
- Importance of IP and DNS configurations in domain environments
- How Azure infrastructure simulates real-world enterprise networks
- The relationship between network settings and domain controller visibility
