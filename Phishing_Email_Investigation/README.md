# Phishing Email Investigation

## Summary

In this lab, I investigated a phishing email campaign that resulted in malicious activity on a Windows endpoint.

The investigation revealed a suspicious email attachment that led to the creation of a PowerShell script, access to a network share, and DNS-based data exfiltration activity using nslookup.

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
