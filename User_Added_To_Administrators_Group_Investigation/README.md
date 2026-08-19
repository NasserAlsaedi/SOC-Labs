# User Added To Administrators Group Investigation

## Summary

In this lab, I simulated a suspicious account privilege change by adding a local user account to the Administrators group on a Windows Server 2019 system.

Using Splunk Enterprise, I investigated Windows Security Event ID 4732 and verified that the account "support123" was successfully added to the local Administrators group by the Administrator account.

## Tools Used

- Windows Server 2019
- PowerShell
- Splunk Enterprise
- VirtualBox

## Findings

- User added to Administrators group detected
- Windows Security Event ID 4732 identified
- Added user: support123
- Target group: Administrators
- Action performed by: Administrator
- Administrative group membership change successfully detected in Splunk
- Detection Result: Successfully Detected (Simulated Activity)

## Skills Demonstrated

- Administrative Group Membership Monitoring
- Windows Security Log Analysis
- Security Group Monitoring
- Splunk Investigation
- Event ID Analysis
- Alert Investigation

## MITRE ATT&CK

- T1098 - Account Manipulation
