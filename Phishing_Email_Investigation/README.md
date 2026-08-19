# Phishing Email Investigation

## Summary

This investigation was completed as part of a simulated SOC scenario using the TryHackMe SOC Simulator. I analyzed and correlated multiple security alerts involving a phishing email, PowerShell activity, network share access, and DNS-based exfiltration to determine the scope of the incident and reach a True Positive verdict.

## Tools Used

- TryHackMe SOC Simulator
- Splunk SIEM
- Sysmon
- Windows Logs
- PowerShell

## Findings

- Suspicious email attachment identified
- Malicious archive file detected
- PowerShell script (PowerView.ps1) created in Downloads folder
- Network share accessed using net.exe
- DNS exfiltration activity detected using nslookup.exe
- Multiple correlated alerts confirmed malicious activity
- Verdict: True Positive

## Skills Demonstrated

- Phishing Investigation
- Alert Triage
- Sysmon Log Analysis
- Process Investigation
- PowerShell Analysis
- DNS Exfiltration Detection
- Incident Reporting

## MITRE ATT&CK

- T1566 - Phishing
- T1059.001 - PowerShell
- T1048 - Exfiltration Over Alternative Protocol
