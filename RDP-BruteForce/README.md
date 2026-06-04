# RDP Brute Force Investigation

## Summary

In this lab, I simulated an RDP brute force attack from a Kali Linux machine targeting a Windows Server 2019 system in my VirtualBox SOC environment.

Using Splunk Enterprise, I investigated multiple failed login attempts and analyzed Windows Security Event ID 4625 logs. The investigation identified the source IP address, attacker workstation, failed account name, and authentication details.

## Tools Used

- Kali Linux
- Windows Server 2019
- Splunk Enterprise
- VirtualBox

## Findings

- Multiple failed RDP login attempts detected
- Event ID 4625 (Failed Logon)
- Source Host: Kali Linux
- Source IP: 192.168.56.108
- Target Host: Windows Server 2019
- Verdict: True Positive

## Skills Demonstrated

- Log Analysis
- Splunk Investigation
- Windows Event Analysis
- RDP Brute Force Detection
- Incident Investigation

MITRE ATT&CK:
- T1110 - Brute Force
