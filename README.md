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

## ⚙️ Key Configurations

- **OUs:** Created for departments (e.g., HR, IT, Finance)
- **GPOs:** Enforced password policy, desktop settings, software restrictions
- **Logon Scripts:** Mapped network drives per user group
- **DNS & DHCP:** Configured with static IP reservations and forward lookup zones
- **Permissions:** Role-based folder access using security groups

## 🛡️ Security Best Practices Applied

- Enforced complex passwords and lockout policy
- Disabled guest accounts
- Used separate Admin and User accounts
- Auditing enabled for logon and file access events
- Group-based delegation and access control

> All steps documented in [documentation/setup-steps.md](documentation/setup-steps.md)

## 🛠️ Tools & Technologies

- Windows Server 2022
- Windows 10 Clients
- Active Directory, DNS, DHCP, GPO
- PowerShell, VirtualBox/VMware/Hyper-V

## 📘 Documentation

- [Setup Instructions](documentation/setup-steps.md)
- [Example GPOs](documentation/gpo-examples.md)
- [Security Best Practices](documentation/security-best-practices.md)

## 📌 Notes

- The lab was built using local virtual machines for a fully offline setup
- All configurations follow real-world IT standards
- Screenshots, exports, and sample scripts included

## 📧 Contact

For questions or feedback, reach out via GitHub Issues or connect on [https://www.linkedin.com/in/liran-karen/](https://www.linkedin.com/in/liran-karen/)

