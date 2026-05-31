
# 🏢 Active Directory Lab – MobileHub
This project is a self-built Active Directory lab designed to simulate a real-world enterprise domain environment. It demonstrates core IT Support and SOC Analyst skills including identity management, user administration, and domain configuration.

<img width="900" height="500" alt="Screenshot 2026-05-26 at 3 26 54 pm" src="https://github.com/user-attachments/assets/2c095960-0bcf-4811-8eba-1cbd828b9865" />

## 🖥️ Environment

- 💻 Windows Server (2019/2022)
- 👥 Active Directory Domain Services (AD DS)
- 🖥️ Windows 10/11 Client Machines
- 🖥️ [VirtualBox](https://www.virtualbox.org/)

## 🌐 Network Setup
- Network Name: `AD Network` 
- IPv4 Network CIDR: `10.0.2.0/24`
- Enable DHCP ✔
> 💡 NAT Network allows your VMs to communicate and access the internet. \
> ⚠️ Ensure both AD & Windows Client Networks is selected to NAT network
  
## 🎥 Video


#### Summary of Configuration
- Installed Active Directory Domain Services (AD DS)
- Promoted server to Domain Controller
- Created domain: **MobileHub.local**
- Configured DNS for domain resolution
- Verified domain functionality for client join

#### User Configuration
- Created domain user accounts
- Assigned users to departmental structures (IT, HR, Sales)
- Organised users within appropriate Organizational Units (OUs)

#### Group Management
- Created security groups for access control (RBAC)
- Created distribution groups for communication
- Assigned users based on department roles


## 🔗Next Project

🔐 [Project 2 - IT Helpdesk Ticketing Simulation](https://github.com/jasikathapa/IT-Helpdesk-Ticketing-Simulation.git)
