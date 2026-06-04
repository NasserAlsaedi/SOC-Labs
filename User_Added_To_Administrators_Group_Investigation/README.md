# User Added To Administrators Group Investigation

## Summary

In this lab, I simulated a privilege escalation activity by adding a local user account to the Administrators group on a Windows Server 2019 system.

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
- Privilege escalation activity successfully detected in Splunk
- Verdict: True Positive

## Skills Demonstrated

- Privilege Escalation Detection
- Windows Security Log Analysis
- Security Group Monitoring
- Splunk Investigation
- Event ID Analysis
- Incident Investigation
