# Scenario 03 — Disk Management Access Rights Warning

## Issue

Disk Management could not be accessed fully while logged in as a standard domain user.

## Environment

- Client: WIN10-CLIENT
- Domain: shirleylab.local
- Logged-in user: shirleylab\hr.user1

## Symptoms

Disk Management displayed an access rights warning and could not connect to the Virtual Disk Service.

## Cause

Disk Management requires administrator permissions because it controls disk and partition-level settings.

## Resolution

Computer Management was opened as administrator, then Disk Management was accessed from there.

## Skills Demonstrated

- Disk Management troubleshooting
- Administrator access control
- Windows endpoint maintenance
- Safe handling of disk tools
