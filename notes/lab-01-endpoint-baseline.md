# Lab 01 — Endpoint Baseline & Local User Management

## Objective

The objective of this lab was to practise basic Windows endpoint configuration and local user management on a Windows 10 Pro client machine joined to an Active Directory domain.

## Lab Environment

| Component | Details |
|---|---|
| Virtualisation | Oracle VirtualBox |
| Client OS | Windows 10 Pro |
| Client Name | WIN10-CLIENT |
| Domain | shirleylab.local |
| Logged-in User | shirleylab\hr.user1 |

## Tasks Completed

- Checked system information using `msinfo32`
- Confirmed the computer name and domain membership using `sysdm.cpl`
- Opened Computer Management with administrator credentials
- Created a local standard user account
- Created a local administrator user account
- Added `local.admin` to the local Administrators group
- Verified users and group membership using PowerShell commands

## Local Users Created

| User | Purpose |
|---|---|
| local.standard | Local standard user account for endpoint support practice |
| local.admin | Local administrator account for endpoint support practice |

## Commands Used

```powershell
whoami
hostname
net user
net localgroup administrators
