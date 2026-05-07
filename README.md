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


### ✅ Windows Server Configuration
![Windows Server](image/server-config.jpg)

### ✅ Client Joined to Domain
![Client Domain](image/client-domain.png)
  

---

## 🔹 Configurations

### ✅ Active Directory
- Created and managed user accounts  
- Managed computer objects  

![Active Directory](image/ad-user.png)

---

# 🌐 DNS Configuration

Configured Active Directory-integrated DNS with forward and reverse lookup zones for hostname resolution.

## 🔹 DNS Zone
![DNS Zones](image/dns-zones.png)

## 🔹 Forward Lookup Zone
![DNS Forward](image/dns-forward.png)

## 🔹 Reverse Lookup Zone
![DNS Reverse](image/dns-reversed.png)

## ✅ DNS Resolution Test
![Verify DNS Connection](image/verifying-serverip.jpg)



### ✅ Group Policy (GPO)

#### 🔐 Account Lockout Policy
- Locks account after 3 incorrect password attempts  
- Automatically unlocks after 3 minute  

![GPO Lockout](image/gpo-lockout.png)

### ✅ Locked User Account

Verified account lockout behavior after multiple failed login attempts.

![Locked User](image/account-locked.png)

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
