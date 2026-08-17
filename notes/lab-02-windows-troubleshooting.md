# Lab 02 — Windows Update, Device Manager, Event Viewer & Services

## Objective

The objective of this lab was to practise checking common Windows endpoint troubleshooting tools used in IT Support and Service Desk roles.

## Lab Environment

| Component | Details |
|---|---|
| Virtualisation | Oracle VirtualBox |
| Client OS | Windows 10 Pro |
| Client Name | WIN10-CLIENT |
| Domain | shirleylab.local |
| Logged-in User | shirleylab\hr.user1 |

## Tasks Completed

- Checked Windows Update status
- Opened Device Manager as a standard domain user
- Observed the standard user permissions warning
- Opened Device Manager with administrator permissions
- Reviewed device categories and hardware status
- Opened Event Viewer
- Checked Windows System logs
- Checked Windows Application logs
- Opened the Services console
- Reviewed Windows services and startup status

## Tools Used

- Windows Update Settings
- Device Manager
- Event Viewer
- Services Console
- Computer Management
- User Account Control

## Evidence Collected

- `06-windows-update-status.png`
- `07-device-manager-standard-user-warning.png`
- `08-device-manager-admin-view.png`
- `09-event-viewer-system-logs.png`
- `10-event-viewer-application-logs.png`
- `11-services-console.png`

## Troubleshooting Notes

When opening Device Manager as a standard domain user, Windows displayed a warning explaining that device settings could be viewed but administrator permission was required to make changes.

This showed the importance of standard user restrictions, User Account Control, and administrator credentials when troubleshooting endpoint hardware or device issues.

Device Manager also showed a device warning in the lab environment, which is useful practice for identifying missing drivers or hardware-related issues.

## What I Learned

This lab helped me understand where IT Support technicians check common endpoint issues in Windows.

I practised using Windows Update, Device Manager, Event Viewer, and Services to review system health, hardware status, logs, and service configuration.

The lab also helped me understand why administrator permissions are often required when making system-level changes on a Windows endpoint.
