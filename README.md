MAKA Company Windows Server Infrastructure 

This project demonstrates the design and implementation of a complete Windows Server infrastructure for a small-to-medium enterprise environment named MAKA Company.

The lab was built using Windows Server, Active Directory Domain Services (AD DS), Group Policy, DHCP, DNS, IIS, and File & Print Services to simulate a real-world corporate network.

Features Implemented

- Active Directory Domain: maka.local
- Organizational Units (OUs) for:
  - Human Resources (HR)
  - Sales
  - Development (DEV)
  - Information Technology (IT)
- User and Group Management
- Password and Account Lockout Policies
- Group Policy Management (GPO)
- Remote Desktop & Remote Assistance Configuration
- USB Storage Restrictions
- DHCP Server with Scope, Exclusions, and Failover
- Additional Domain Controller (ADC)
- DNS Configuration and Round Robin Load Distribution
- IIS Web Server Deployment
- Departmental Shared Folders and Mapped Network Drives
- Public Shared Folder with Disk Quota
- Network Printer Deployment and Management
- Active Directory Recycle Bin
- Windows 10 Client Domain Join
- Automated Daily Backup Configuration

Special Configuration

- Members of the IT Group are excluded from the GPO that restricts access to Control Panel and Task Manager.
- DNS Round Robin was configured to distribute requests between both domain controllers hosting IIS.

Technologies Used

- Windows Server
- Active Directory Domain Services (AD DS)
- DNS
- DHCP
- Group Policy
- IIS Web Server
- File Server
- Print Server
- Windows 10

Objective

The goal of this project is to gain hands-on experience with Windows Server administration and enterprise infrastructure deployment while simulating common services used in production environments.
