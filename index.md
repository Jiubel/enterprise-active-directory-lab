---
layout: default
title: Enterprise Active Directory Lab
---

# 🛠️ Enterprise Active Directory & Network Lab

## Overview
Designed and implemented a Windows-based enterprise lab environment to simulate core infrastructure services including Active Directory, DNS, DHCP, and network routing.

The lab consists of a Windows Server 2019 Domain Controller and a Windows 10 client connected through an isolated internal network, with NAT configured to allow external connectivity.

---

## Lab Architecture

![Lab Diagram](/images/lab-diagram.png)

---

## Key Components

### Domain Controller (Windows Server 2019)
- Active Directory Domain Services (AD DS)
- DNS Server
- DHCP Server
- RRAS (NAT Gateway)
- Internal IP: 172.16.0.1/24

### Network Configuration
- Internal Network: 172.16.0.0/24
- DHCP Scope: 172.16.0.100–200
- Gateway: 172.16.0.1
- DNS: 172.16.0.1

### Client System (Windows 10)
- DHCP Enabled
- Domain Joined (mydomain.com)
- Verified authentication and connectivity

---

## Automation

Used PowerShell to automate bulk user provisioning using a structured input file.

![PowerShell Automation](/images/powershell-bulk-user-creation.png)

---

## Validation

### Domain Authentication
![Domain Login](/images/domain-user-login-proof.png)

### Network Connectivity
![Connectivity Test](/images/client-internet-connectivity.png)

---

## Key Skills Demonstrated

- Active Directory Administration  
- Windows Server Configuration  
- Network Services (DNS, DHCP, NAT)  
- PowerShell Automation  
- System Integration & Troubleshooting  

---

## Summary
This project demonstrates hands-on experience with enterprise-level Windows infrastructure, including identity management, networking, and automation. The environment reflects a practical implementation of services commonly used in IT support and system administration roles.
