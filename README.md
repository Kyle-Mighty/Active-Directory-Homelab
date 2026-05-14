# Active-Directory-Homelab

---

# Purpose

This project stimulates a real-world domain environment using virtual machines(VM):
  Skills Demonstrated
  - User/Group Management
  - Organizational Units(Ou)
  - User Account Unlock
  - User Password Reset

---

# Tools Used
- Windows Server 2022
- Active Directory Domain Services
- VMware

---

# Domain Controller Login

Objective: Creating Groups, Organizational Units, and Users

A Windows Server domain controller was configured with Active Directory Domain Services
<img width="1540" height="912" alt="Screenshot 2026-05-13 191817" src="https://github.com/user-attachments/assets/4e9876e8-6ce7-4d03-b11d-fc45d926ae56" />



# Server Dashboard
<img width="1021" height="732" alt="Screenshot 2026-05-13 192019" src="https://github.com/user-attachments/assets/c8483d85-138b-434e-800b-3e2d32cc7a58" />

---
# Navigating to Active Directory Users and Computers
<img width="1024" height="767" alt="Directions to (AD US)" src="https://github.com/user-attachments/assets/1abc4efc-afc1-48fb-8a8b-b7c830429d13" />


# Domain and OU Structure
A domain (EastLake.local) was created with Organizational Units (OUs) to reflect departments:
 - USA
 - Europe
 - Asia

# Domain Structure
<img width="1021" height="159" alt="Domain Structure" src="https://github.com/user-attachments/assets/0abd63e9-20a0-43f3-84ba-0463c5b68367" />

# Domain Design
<img width="1024" height="296" alt="Ou Design" src="https://github.com/user-attachments/assets/4044755a-8960-438f-bb60-7e500e851db2" />

---

# Steps To Creating (OUs)
 Right-click the domain controller name (EastLake.local) -> New -> Organizational Unit
<img width="1022" height="725" alt="Creating Ous 1" src="https://github.com/user-attachments/assets/3cd17fdb-4957-428c-bb00-0eb958c36c42" />

# Name The Files
Created 3 (Ous) USA, Europe, and Asia
<img width="1035" height="695" alt="Name Files" src="https://github.com/user-attachments/assets/18c4e5f5-d56b-455f-b660-b27d40049367" />

# Created Ous Within The Department OUs
Added the following groups: Users, Computers and Servers to the Previous (Ous)
<img width="1021" height="727" alt="Created Ous Within The Department OUs" src="https://github.com/user-attachments/assets/06dab16e-bee5-46cb-90b2-9d3549663c39" />


---
 
# Creating Groups

Go to designated Ou -> Right click -> Group
<img width="1035" height="685" alt="Creating Users" src="https://github.com/user-attachments/assets/ce7d9949-8ea6-4512-84c1-2867052ec4e2" />

# Name The Group 
Type in a name for the Group and keep the group scope global. Hit ok
<img width="1032" height="682" alt="Name Group" src="https://github.com/user-attachments/assets/dfebd172-4a06-424c-80cd-caa41dbbf09d" />

# Created a Security Group and Distribution Group
<img width="1022" height="136" alt="Created a Security Group and Distribution Group" src="https://github.com/user-attachments/assets/4d7a4580-3a01-4b11-974d-3e35d78dbc0c" />

---

# Creating Users
Go to Department where you are needed -> Right click Users -> New -> User

# Create a Name and User Login Name
<img width="1023" height="727" alt="Create a Name and User Login Name" src="https://github.com/user-attachments/assets/201a0096-f1b1-4aab-ad3d-01800dfad1fa" />

# Create a Password
Hit ok and user is created
<img width="434" height="379" alt="Create a Password" src="https://github.com/user-attachments/assets/80cc481e-a0e7-4ba5-a84b-1982c58867c1" />

---











