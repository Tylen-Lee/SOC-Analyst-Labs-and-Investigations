# Data Exfiltration Investigation

## Objective

The objective of this investigation was to identify and analyse suspicious outbound traffic associated with potential data exfiltration techniques within a controlled lab environment.

The investigation focused on detecting covert communication methods such as DNS tunneling and FTP-based file transfers through manual log analysis and network traffic inspection.

Using Linux command-line analysis techniques, suspicious hosts, external destinations, and sensitive file transfers were identified to better understand attacker behaviour and exfiltration methodologies.

---

## Key Findings

- Identified suspicious DNS tunneling activity  
- Detected repeated requests to suspicious domains  
- Traced malicious DNS activity back to the host 192.168.1.103  
- Confirmed FTP-based file uploads using the FTP STORE action  
- Identified sensitive files being transferred externally  
- Detected repeated uploads to a centralized external destination  
- Analysed potential Command & Control (C2) style communication patterns  

---

## Skills Learned

- Data exfiltration analysis  
- DNS tunneling investigation  
- FTP traffic analysis  
- ICMP traffic analysis
- HTTP traffic analysis
- Linux log analysis techniques  
- Threat detection and IOC identification  
- Network traffic inspection  
- Investigative and analytical methodology  

---

## Tools & Technologies

- Kali Linux  
- Linux Command Line  
- Wireshark  
- DNS Logs  
- FTP Logs  
- HTTP Logs
- ICMP Logs
- PCAP Analysis  
- Network Traffic Analysis Techniques  

---

## Lab Report

[![View Report](https://img.shields.io/badge/View-Full%20PDF-lime?style=for-the-badge)](./02-data-exfiltration-investigation/data-exfiltration-investigation.pdf)




---

## Summary

This investigation demonstrated how attackers may abuse protocols such as DNS and FTP to transfer data outside an organization.

Manual log analysis techniques were used to identify suspicious communication patterns, investigate outbound connections, and confirm successful file transfer activity associated with data exfiltration.
