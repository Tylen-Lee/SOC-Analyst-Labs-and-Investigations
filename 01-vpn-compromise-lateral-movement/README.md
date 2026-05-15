# VPN-Compromise-&-Lateral-Movement-Investigation-THM

## Objective

The objective of this project is to simulate and investigate a real-world network security incident by analysing multiple log sources within a controlled lab environment using the comand line interface.

This lab focuses on identifying and reconstructing a multi-stage attack involving VPN brute-force access, internal reconnaissance, lateral movement, and command-and-control (C2) activity.

Using manual log analysis techniques, the goal is to understand how attackers gain initial access, move within a network, and establish persistence, while developing practical skills in incident response and threat detection.

Additionally, this investigation highlights the importance of log visibility, monitoring, and proactive security measures in defending enterprise environments.


## 🔍 Key Takeaways

- Identification of VPN brute-force attacks through log analysis  
- Detection of compromised user accounts and unauthorized access  
- Understanding how attackers gain internal network access via VPN  
- Analysis of internal reconnaissance and service enumeration  
- Recognition of lateral movement techniques using SMB (port 445)  
- Detection of IDS alerts indicating suspicious and exploit activity  
- Identification of Command & Control (C2) beaconing behaviour  
- Awareness of potential data movement and exfiltration techniques  
- Understanding the importance of correlating multiple log sources  


## 🧠 Skills Learned

- Log analysis (Firewall, VPN, IDS logs)  
- Incident response and attack chain reconstruction  
- Network traffic analysis and interpretation  
- Threat detection and behavioural analysis  
- Identifying brute-force and credential-based attacks  
- Lateral movement detection techniques  
- Basic understanding of C2 communication patterns  
- Analytical thinking and investigative methodology  


## 🛠 Tools & Technologies

- Kali Linux  
- Linux Command Line (grep, cut, sort, uniq)  
- Firewall Logs  
- VPN Authentication Logs  
- IDS Alert Logs  
- Network Monitoring & Log Analysis Techniques  


## 🔗 MITRE ATT&CK Mapping

This lab activity can be mapped to the following adversary tactics and techniques:

- **Initial Access** – VPN Brute Force / Valid Accounts  
- **Persistence** – Continued access via VPN session  
- **Discovery** – Internal network scanning and service enumeration  
- **Lateral Movement** – SMB exploitation attempts (Port 445)  
- **Command & Control** – Beaconing to external C2 infrastructure  
- **Exfiltration (Potential)** – Data transfer over SMB  


## 📄 Lab Report

Click below to view the full investigation report:

[![View Report](https://img.shields.io/badge/View-Full%20PDF-lime?style=for-the-badge)](VPN-Compromise-&-Lateral-Movement-Investigation-THM.pdf)


<img width="1034" height="432" alt="image" src="https://github.com/user-attachments/assets/cc1fd71f-5172-4321-ab91-c6a0e9b1451d" />
















