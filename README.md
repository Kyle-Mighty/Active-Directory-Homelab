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
Hit next and user is created

<img width="434" height="379" alt="Create a Password" src="https://github.com/user-attachments/assets/80cc481e-a0e7-4ba5-a84b-1982c58867c1" />

---
# Account Unlock
## Example scenario of User having trouble accessing their account

Hello IT Support

I’m currently unable to log into my account this morning. After entering my username and password, I receive a message saying that my account credentials are incorrect, even though I believe I’m using the right password.

I’ve already tried restarting my computer and attempting to log in multiple times, but I’m still unable to access my account. I need access as soon as possible because I have work files and email messages I need for today.

Could you please assist me with resetting my password or checking if there is an issue with my account?

Thank you,

John Brown
USA Department

# Find The User
Open Active Directory -> Go to designated Department -> Right-click Users -> Click Find
<img width="1018" height="426" alt="Find User" src="https://github.com/user-attachments/assets/f00d2209-821f-42bd-b090-939f86f799b9" />

# Type Name of User
Search up their name -> Click Find Now -> Double Click The User
<img width="596" height="568" alt="Type Name of User" src="https://github.com/user-attachments/assets/5c26722b-1c1d-4bd2-9b78-873f212e1726" />

# Click on Account
<img width="409" height="540" alt="Click on Account" src="https://github.com/user-attachments/assets/7c96ab58-d0df-4515-976a-b189e3515be2" />

# Click on The Unlock Account Check Box
Click ok. Users account is now unlocked
<img width="409" height="534" alt="Click on The Unlock Account Check Box" src="https://github.com/user-attachments/assets/ebe19923-9bef-4894-8ac1-447068379dce" />

---

# Password Reset
## Example scenario of User having trouble accessing their account

Hello IT Support,

I am unable to access my account because I forgot my current password. Could you please assist me with resetting my password so I can regain access to my email and work applications?

Thank you for your help.

Best regards,

Sarah Johnson
Accounting Department

# Find The User
Open Active Directory -> Go to designated Department -> Right-click Users -> Click Find
<img width="1018" height="426" alt="Find User" src="https://github.com/user-attachments/assets/f00d2209-821f-42bd-b090-939f86f799b9" />

# Type Name of User (Jane Rose)
Search up their name -> Click Find Now -> Right Click The User -> Click Reset Password
<img width="516" height="564" alt="Type Name of User (Jane Rose)" src="https://github.com/user-attachments/assets/b82cf835-f901-4bf7-b2f0-f2d741834c9f" />

# Create New Password
Click ok. Password changed
<img width="514" height="512" alt="Create New Password" src="https://github.com/user-attachments/assets/9bd95828-c7e1-419c-9a7d-3c3e446d9137" />
<img width="346" height="149" alt="Password Successfully Changed" src="https://github.com/user-attachments/assets/1420dfe3-d5c3-45f3-b3dd-199cae2426e4" />

---



























