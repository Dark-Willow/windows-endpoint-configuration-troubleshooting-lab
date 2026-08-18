# Lab 03 — Disk Management & Basic Windows Maintenance

## Objective

The objective of this lab was to practise basic Windows disk management and maintenance checks commonly used in IT Support and Service Desk roles.

## Lab Environment

| Component | Details |
|---|---|
| Virtualisation | Oracle VirtualBox |
| Client OS | Windows 10 Pro |
| Client Name | WIN10-CLIENT |
| Domain | shirleylab.local |
| Logged-in User | shirleylab\hr.user1 |

## Tasks Completed

- Opened Disk Management as a standard domain user
- Observed the permissions warning when accessing Disk Management without administrator rights
- Opened Disk Management with administrator permissions
- Reviewed disk layout, partitions, and C: drive status
- Checked Windows Storage settings
- Reviewed startup apps in Task Manager
- Opened Disk Cleanup
- Ran System File Checker using `sfc /scannow`
- Ran Check Disk using `chkdsk C:`

## Tools Used

- Disk Management
- Computer Management
- Windows Storage Settings
- Task Manager
- Disk Cleanup
- Administrator Command Prompt
- System File Checker
- Check Disk
- User Account Control

## Evidence Collected

- `12-disk-management-standard-user-warning.png`
- `13-disk-management-overview.png`
- `14-storage-settings.png`
- `15-task-manager-startup-apps.png`
- `16-disk-cleanup.png`
- `17-sfc-scan-result.png`
- `18-chkdsk-scan-result.png`

## Commands Used

```powershell
sfc /scannow
chkdsk C:
