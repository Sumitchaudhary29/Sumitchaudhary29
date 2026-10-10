# Windows Server & Active Directory Home Lab

A hands-on lab I built on VMware Workstation to practise Windows Server and Active Directory the way they are used in real IT support.

## Lab Environment
- Hypervisor: VMware Workstation
- Server: Windows Server (Domain Controller)
- Client: Windows 11 PC

## What I Did

### 1. Setting up the virtual machines
- Created a VM in VMware Workstation and installed Windows Server
- Created a second VM and installed a Windows 11 client PC

(screenshot: both VMs running)

### 2. Active Directory setup
- Installed the Active Directory Domain Services (AD DS) role
- Promoted the server to a domain controller and set the domain name
- Joined the client PC to the domain (moved it from workgroup to domain)
- Checked communication between the server and client using ping

(screenshot: AD DS installed, client joined to the domain)

### 3. Users, groups and OUs
- Created and managed user accounts, groups and Organizational Units (OUs)
- Applied user restrictions such as logon hours

### 4. Group Policy
- Applied Group Policies to domain users
- Forced policy updates on the client and checked that they applied

### 5. DNS and DHCP
- Configured DNS and DHCP services

### 6. File sharing
- Created shared folders and configured NTFS and share permissions for users and groups

### 7. Support scenarios I practised
- Password reset and account unlock
- Client PC not connecting to the domain
- User unable to log in
- Group Policy not applying

## Commands I used for checking and troubleshooting
ipconfig, ping, nslookup, gpupdate

## Planned next
- Child domain
- Domain replication

