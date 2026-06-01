
# 🏢 Active Directory Lab – MobileHub
This project is a self-built Active Directory lab designed to simulate a real-world enterprise domain environment. It demonstrates core IT Support and SOC Analyst skills including identity management, user administration, and domain configuration.

<img width="1024" height="450" alt="Screenshot 2026-05-26 at 3 26 54 pm" src="https://github.com/user-attachments/assets/2c095960-0bcf-4811-8eba-1cbd828b9865" />

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

#### 👉 [Click here to watch](https://1drv.ms/f/c/6f9c3032e3dd4069/IgCd9x0H1zGMTp1e0k81C1P9Acv7jQkTTeLqBYUSneoOWb4?e=pbo7Ug)

## ⚙️ Project Steps

#### 1️⃣ Active Directory Domain Setup
- Installed Active Directory Domain Services (AD DS)
- Promoted Windows Server to Domain Controller
- Created new domain: **MobileHub.local**
- Configured DNS for domain name resolution\
  <img width="300" height="200" alt="image" src="https://github.com/user-attachments/assets/e2a66200-6fc3-46c2-9d32-5c9874fb30be" /> 

#### 2️⃣ Active Directory Structure
- Created Organizational Units (OUs):
  - IT Department  
  - HR Department  
  - Sales Department  

#### 3️⃣ User Configuration
- Created domain user accounts
- Assigned users to departmental structures (IT, HR, Sales)
- Organised users within appropriate Organizational Units (OUs)
<img width="300" height="200" alt="image" src="https://github.com/user-attachments/assets/f78c92f3-1bac-4c11-8f9b-614a0ad889c3" />

#### 4️⃣ Client Domain Join
- Joined Windows 11 client machine to the domain
- Verified successful domain authentication
- Tested login using domain user credentials

#### 5️⃣  Group Management
- Created security groups for access control (RBAC)
- Assigned users based on department roles
<img width="300" height="200" alt="image" src="https://github.com/user-attachments/assets/4de3cf9c-3143-4407-8e8a-28b64d90817d" />

#### 6️⃣  Verification
- Confirmed Active Directory functionality
- Verified user login and group assignments
- Ensured domain services were working correctly
<img width="300" height="200" alt="image" src="https://github.com/user-attachments/assets/bd622e4a-0acb-4d67-9cbc-d68bd3c74abf" />

#### 7️⃣ Configuring Group Policy (GPO)
- Setting account lockout policy
- Restricting Control Panel access
- Disabling/controlling program access

## 🔗Next Project

🔐 [Project 2 - IT Helpdesk Ticketing Simulation](https://github.com/jasikathapa/IT-Helpdesk-Ticketing-Simulation.git)  







