# Company Network Penetration Test
## Overview
This repository contains the detailed documentation and results of a comprehensive penetration test conducted on a company's virtual corporate network. The primary goal was to audit the network's security, identify vulnerabilities and misconfigurations, and demonstrate potential exploitation risks. By following a "grey box" penetration testing methodology, the project provides insights into the network's security posture and suggests measures to enhance its protection.

## Objectives
Examine the Network: Thoroughly investigate and enumerate the provided corporate network.
Identify Vulnerabilities: Detect vulnerabilities and misconfigurations within the network.
Demonstrate Exploitation Risks: Utilize the gathered information to demonstrate the potential hazards of present vulnerabilities.
Suggest Countermeasures: Determine and recommend ways to remediate vulnerabilities to prevent exploitation.
# Methodology
The penetration testing followed a structured approach, divided into several key phases:

## 1. Network Scanning:

Tools Used: NetDiscover, Nmap, Masscan, hping3
Purpose: Identify open ports, running services, and network architecture.
## 2. Vulnerability Scanning:

Tools Used: Nessus Essentials, OpenVAS
Purpose: Detect vulnerabilities in software versions, configurations, and user input filtering.
## 3. Enumeration:

Techniques: DNS, SNMP, LDAP, NetBIOS, SMB Enumeration
Tools Used: Dig, Host, snmp-check, Ldapsearch, NBTEnum, Rpcclient, Polenum, Enum4linux
Purpose: Gather detailed information about user accounts, groups, password policies, and available shares.
## 4. Password Cracking:

Tools Used: Hydra, DomainPasswordSpray.ps1, Cain, CrackStation
Purpose: Crack passwords using brute force and password spraying techniques.
## 5. System Hacking:

Tools Used: msfconsole, searchsploit, Shellter
Purpose: Exploit identified vulnerabilities to gain unauthorized access and establish a backdoor for future access.


# Key Findings
Identified numerous vulnerabilities, including outdated software versions and misconfigurations.
Discovered critical information such as company domain, user accounts, groups, and password policies.
Successfully cracked several user account passwords and demonstrated potential exploitation through system hacking.
Established a backdoor on the server to maintain access even if vulnerabilities are patched.
# Countermeasures
To address the identified issues, the following countermeasures are recommended:

Implement strict access controls and regular security audits.
Configure firewalls to filter network traffic and minimize exposure.
Regularly update and patch systems and software.
Deploy intrusion detection and prevention systems.
Conduct regular security assessments, including penetration testing and vulnerability assessments.
# Future Work
Despite the extensive work conducted, further exploration is suggested in the following areas:

Analyze accessible shares for sensitive information.
Examine all running services for additional vulnerabilities.
Investigate potential Active Directory misconfigurations.
Conclusion
This project successfully demonstrated the importance of regular security audits and the potential risks associated with network vulnerabilities. By following the outlined countermeasures, organizations can significantly enhance their network security and reduce potential risks.
