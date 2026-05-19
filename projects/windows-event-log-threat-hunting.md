# Windows Event Log Threat Hunting Lab

## Project Summary

This project documents hands-on practice analyzing Windows Event Logs for common SOC analyst investigation scenarios.

The goal is to review Windows security events, identify suspicious or notable activity, and document findings using a structured investigation format.

## Objective

The objective of this lab is to build practical experience with Windows log analysis and threat hunting by reviewing authentication events, privilege activity, PowerShell usage, and suspicious process execution.

## Tools Used

- Windows Event Viewer
- Windows Security Logs
- PowerShell
- Command Prompt
- Screenshots
- Markdown documentation

## Skills Practiced

- Windows Event Log analysis
- Failed login investigation
- Successful login review
- Privilege escalation indicators
- PowerShell activity review
- Suspicious process identification
- SOC-style documentation
- Evidence collection

## Key Windows Event IDs

| Event ID | Description |
|---|---|
| 4624 | Successful logon |
| 4625 | Failed logon |
| 4672 | Special privileges assigned to new logon |
| 4688 | New process created |
| 4720 | User account created |
| 4726 | User account deleted |
| 4732 | User added to local group |
| 1102 | Audit log cleared |

## Lab Setup

This lab uses a Windows system with Event Viewer enabled. Events are reviewed under:

```text
Event Viewer → Windows Logs → Security
