# Windows Event Log Threat Hunting Lab

## Project Summary

This project documents hands-on practice analyzing Windows Event Logs for common SOC analyst investigation scenarios.

The goal of this lab is to review Windows security events, identify suspicious or notable activity, and document findings using a structured investigation format.

## Scenario

A Windows workstation showed signs of suspicious authentication and command-line activity. The objective of this lab is to investigate Windows Event Logs for failed logons, successful logons, privileged access, process creation, and PowerShell activity.

This lab is performed in a safe learning environment using normal Windows activity and built-in Windows logging tools.

## Objective

The objective of this lab is to build practical experience with Windows log analysis and threat hunting by reviewing authentication events, privileged activity, PowerShell usage, and suspicious process execution.

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
- Privileged logon review
- PowerShell activity review
- Suspicious process identification
- SOC-style documentation
- Evidence collection
- Security event correlation

## Key Windows Event IDs

| Event ID | Description | Why It Matters |
|---|---|---|
| 4624 | Successful logon | Confirms that an account successfully authenticated |
| 4625 | Failed logon | May indicate bad password attempts, password guessing, or brute-force activity |
| 4672 | Special privileges assigned to new logon | Shows that an account received administrative or sensitive privileges |
| 4688 | New process created | Shows process execution activity, such as PowerShell or Command Prompt |
| 4720 | User account created | May indicate account creation activity |
| 4726 | User account deleted | May indicate account removal activity |
| 4732 | User added to local group | May indicate privilege escalation or unauthorized group changes |
| 1102 | Audit log cleared | May indicate an attempt to hide activity |

## Lab Setup

This lab uses a Windows system with Event Viewer enabled. Events are reviewed under:

```text
Event Viewer → Windows Logs → Security

