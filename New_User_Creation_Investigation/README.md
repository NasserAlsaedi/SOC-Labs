# New User Creation Investigation

## Summary

In this lab, I simulated the creation of a new local user account on a Windows Server 2019 system in my VirtualBox SOC environment.

Using Splunk Enterprise, I investigated Windows Security Event ID 4720 and confirmed the successful creation of a new account. The investigation identified the account creator, account name, and related user management activity.

## Tools Used

- Windows Server 2019
- PowerShell
- Splunk Enterprise
- VirtualBox

## Findings

- New user account creation detected
- Windows Security Event ID 4720 identified
- Created account: support123
- Account created by: Administrator
- User management activity successfully detected in Splunk
- Detection Result: Successfully Detected (Simulated Activity)

## Skills Demonstrated

- Windows Security Log Analysis
- User Account Monitoring
- Splunk Investigation
- Event ID Analysis
- Security Monitoring
- Alert Investigation

## MITRE ATT&CK

- T1136 - Create Account
