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

# ⚡ PowerShell Administration

Used PowerShell to automate Active Directory administration tasks such as creating Organizational Units (OU), security groups, and domain users.

Configured user accounts and added users to department groups using PowerShell commands, then verified the changes in Active Directory Users and Computers.

---

### ✅ OU and Group Creation using PowerShell

Created Organizational Units and security groups using PowerShell.

![PowerShell OU and Group](images/powershell-ou-group.PNG)

---

### ✅ User Creation using PowerShell

Created domain user accounts using PowerShell commands.

![PowerShell User Creation](images/powershell-user.PNG)

---

### ✅ Added Users to Security Groups

Added users to department security groups using PowerShell.

![PowerShell Group Membership](images/powershell-group-member.PNG)

---

### ✅ Active Directory Verification

Verified that the users and groups were successfully created inside the correct Organizational Unit in Active Directory Users and Computers.

![AD Verification](images/ad-verification.PNG)

---

### ✅ Group Membership Verification

Verified that users were successfully added to the correct security groups.

![Group Verification](images/group-verification.PNG)



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

![Locked User](image/account-lockout.png)

---

#### 🔐 USB Restriction Policy
- Blocked access to external USB devices
-  Configured Group Policy to block access to all removable storage devices.

![USB Restriction Policy](image/usb-policy.PNG)

### ✅ Group Policy Applied

Verified that the removable storage restriction policy was successfully applied.

![GPO Applied](image/gpo-applied.PNG)

### ✅ USB Access Blocked

Verified that removable storage access was denied on the client machine after applying the Group Policy.

![USB Blocked](image/usb.blocked.jpg)


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
