# Scenario 02 — Device Manager Administrator Permission Warning

## Issue

Device Manager displayed a warning when opened as a standard domain user.

## Environment

- Client: WIN10-CLIENT
- Domain: shirleylab.local
- Logged-in user: shirleylab\hr.user1

## Symptoms

Windows allowed the user to view device settings but explained that administrator permissions were required to make changes.

## Cause

Device-level changes require elevated privileges.

## Resolution

Device Manager was opened through Computer Management using administrator credentials.

## Skills Demonstrated

- Device Manager review
- Administrator permission awareness
- Endpoint hardware troubleshooting
- User Account Control
