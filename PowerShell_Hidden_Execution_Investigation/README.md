# Suspicious PowerShell Investigation

## Summary

In this lab, I simulated a suspicious PowerShell execution using hidden execution arguments in my VirtualBox SOC environment.

The command was launched with PowerShell options (-nop and -w hidden) and executed the "net user" command to enumerate local accounts. Using Splunk Enterprise and Sysmon Event ID 1, I investigated the process creation event and analyzed the parent-child process relationship.

## Tools Used

- Windows Server 2019
- PowerShell
- Sysmon
- Splunk Enterprise
- VirtualBox

## Findings

- Suspicious PowerShell execution detected
- Sysmon Event ID 1 captured process creation activity
- Hidden PowerShell arguments identified (-nop -w hidden)
- Parent process: powershell.exe
- Child process: net.exe
- Activity successfully detected in Splunk
- Detection Result: True Positive (Simulated Suspicious Activity)

## Skills Demonstrated

- PowerShell Analysis
- Sysmon Log Analysis
- Splunk Investigation
- Process Creation Monitoring
- Parent-Child Process Analysis
- Incident Investigation

## MITRE ATT&CK

- T1059.001 - PowerShell
