# 🏢 Windows AD Enterprise Lab

This project simulates an enterprise-level Windows Server 2022 environment with Active Directory. It demonstrates core skills in domain setup, user and group management, Group Policy Objects (GPOs), network services, and security hardening—ideal for IT, Helpdesk, and SysAdmin roles.

## 📌 Project Overview

The lab includes:

- ✅ Active Directory Domain Services (AD DS)
- ✅ DNS and DHCP role configuration
- ✅ Organizational Units (OUs) for departments
- ✅ Group Policy Objects for security and user experience
- ✅ Shared drives with permissions
- ✅ Password policies and logon scripts
- ✅ Multiple Windows clients joined to the domain

## 🖥️ Lab Architecture

![Network Diagram](network-diagram.png)  
*A simulated enterprise network using VirtualBox/VMware/Hyper-V*

## 📂 Folder Structure

```plaintext
windows-ad-enterprise-lab/
├── README.md
├── network-diagram.png
├── documentation/
│   ├── setup-steps.md
│   ├── gpo-examples.md
│   └── security-best-practices.md
├── scripts/
│   └── logon-script.bat
└── exports/
    └── gpo-policies.txt
