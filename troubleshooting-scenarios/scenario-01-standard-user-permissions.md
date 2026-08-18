# Scenario 01 — Standard User Permission Limitation

## Issue

While logged in as a standard domain user, some Windows management tools required administrator permissions.

## Environment

- Client: WIN10-CLIENT
- Domain: shirleylab.local
- Logged-in user: shirleylab\hr.user1

## Symptoms

The standard domain user could open some tools for viewing, but could not make system-level changes.

## Cause

The logged-in account did not have local administrator permissions on the Windows endpoint.

## Resolution

The required tools were opened using administrator credentials.

## Skills Demonstrated

- User Account Control awareness
- Standard user vs administrator permissions
- Endpoint support troubleshooting
- Windows access control understanding
