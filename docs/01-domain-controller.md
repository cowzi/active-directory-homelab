# Domain Controller Setup

## Overview
A domain controller is a centralised server in a computer network that manages security, user ids, and access permissions.
I've configured the DC by getting started with AD DS (Active Directory Domain Services).

## Environment
- Server: DC01
- Domain: cowlab.local
- IP: 192.168.1.10

## Steps taken
1. Installed AD DS role in Server Manager
2. Promoted DC01 to Domain Controller
3. Set root domain to cowlab.local
4. Verified AD DS showing green in Server Manager

## Screenshots

### Server Manager - AD DS Role Active
![AD DS Green](/docs/screenshots/phase2/server-manager-adds.png)

### Active Directory Users and Computers
![AD UC Open](/docs/screenshots/phase2/aduc-open.png)
