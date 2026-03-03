# Active-Directory-Home-Lab
# Overview
This project demonstrates setting up a Windows Server Active Directory lab in a virtual environment.

The lab covers:

- Windows Server Installation
- Active Directory Domain Services setup
- Domain Controller creation
- Domain Admin login
- Organizational Units (OUs) creation
- User creation
- Group membership configuration
- Password policy configuration
- Audit policy configuration
- Security event log monitoring
- Simulated failed and successful logins

# Lab Architecture

Domain Controller:
- Windows Server 2022
- Static IP: 192.168.50.10
- Domain: corp.local

Client Machine:
- Windows 11 Pro
- Joined to corp.local

# Step-by-Step Screenshots

1. Server Installed
![Server Installed](01-server-install.png)
2. Active Directory Role Installed
![AD DS Installed](02-add-ad-role.png)
3. Domain Created
![Domain Created](03-domain-created.png)
4. Domain Admin Login
![Domain Admin Login](04-domain-admin-login.png)
5. Organizational Units Created
![OUs Created](05-ous-created.png)
6. Users Created
![Users Created](06-users-created.png)
7. Group Membership Configured
![Group Membership](07-group-membership.png)
8. Password Policy Set
![Password Policy](08-password-policy.png)
9. Audit Enabled
![Audit Enabled](09-audit-enabled.png)
10. Failed Login Attempt
![Failed Login](10-failed-login.png)
11. Successful Login
![Successful Login](11-successful-login.png)

# Security Event IDs Observed
- 4624 - Successful Login
- 4625 - Failed Login
- 4723 - Password Change Attempt
- 4724 - Password Reset

# Skills Demonstrated
- Windows Server Administration
- Active Directory Administration
- Organizational Unit (OU) Creation
- User and Group Management
- Password Policy Configuration
- Audit Policy Setup
- Security Event Monitoring
- Domain Enivronment Troubleshooting

