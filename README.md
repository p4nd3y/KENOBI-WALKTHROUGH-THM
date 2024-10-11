Description
This repository contains a detailed walkthrough of the Kenobi box on TryHackMe. The Kenobi room focuses on enumerating and exploiting various Linux-based services and vulnerabilities to achieve system compromise and root access. It covers techniques such as SMB enumeration, NFS exploitation, and privilege escalation.

Objectives
The following objectives are covered in the walkthrough:

Network Enumeration: Identify open services and gather useful information.
Exploitation: Exploit identified vulnerabilities in SMB and NFS to gain access.
Privilege Escalation: Use kernel exploits to escalate privileges and gain root access.
Tools Used
nmap: For network scanning and service detection
smbclient: For interacting with SMB shares
enum4linux: For enumerating SMB information
rpcclient: To query RPC services
NFS utilities: For mounting NFS shares
searchsploit: To find potential kernel exploits
Metasploit: For exploitation of discovered vulnerabilities
Walkthrough Overview
The walkthrough is broken down into the following key sections:

Reconnaissance: Using nmap to discover open ports and services.
SMB Enumeration: Utilizing smbclient and enum4linux to identify SMB shares and valuable information.
NFS Exploitation: Mounting NFS shares to retrieve files and discover weaknesses.
Initial Access: Exploiting the vulnerabilities in exposed services to gain a foothold on the system.
Privilege Escalation: Elevating privileges by exploiting known kernel vulnerabilities to obtain root access.
How to Use
Follow the step-by-step guide provided in this repository to replicate the exploitation process.
Ensure you have the necessary tools installed (nmap, smbclient, etc.) and root privileges if required.
