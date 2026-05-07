# IT-Support-System-Admin-Lab
Active Directory, DNS, and GPO home lab project

## 📌 Overview
This project demonstrates a hands-on IT support lab built using virtualization. It simulates real-world user management, system configuration, and troubleshooting tasks.

---

## 🔹 Tools & Technologies
- Oracle VM VirtualBox  
- Windows Server 2022  
- Windows 10  
- Active Directory  
- DNS Server  

---

## 🔹 Lab Setup
- Created virtual machines using VirtualBox  
- Installed Windows Server 2022 and Windows 10  
- Promoted server to Domain Controller  
- Joined Windows 10 client to domain  

---

## 🔹 Configurations

### ✅ Active Directory
- Created and managed user accounts  
- Managed computer objects  

![Active Directory](image/ad-user.png)

---

### ✅ DNS Configuration
- Configured forward lookup zone  
- Configured reverse lookup zone  
- Verified domain name resolution  
![DNS Configuration](DNS Configuration/dns zones.png)

---

### ✅ Group Policy (GPO)

#### 🔐 Account Lockout Policy
- Locks account after 3 incorrect password attempts  
- Automatically unlocks after 3 minute  

![GPO Lockout](images/gpo-lockout.png)

---

#### 🔐 USB Restriction Policy
- Blocked access to external USB devices  

---

### ✅ Audit Policy
- Enabled logging for account lockout and login failures  


---
### ✅ File Sharing Configuration
- Configured shared folders on Windows Server  
- Assigned access permissions to specific users  
- Tested file access from client machine within domain  

Below is the shared folder configuration and access from client:

![File Sharing](images/file-sharing.png)

## 🔹 Troubleshooting Scenarios
- Resolved user password reset issues  
- Unlocked locked user accounts  
- Diagnosed login failures using audit logs  

![User Issue](images/user-issue.png)

---

## 🔹 Outcome
- Gained practical experience in IT support tasks  
- Improved troubleshooting and system administration skills  
