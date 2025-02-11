Arts Tailor Shoppe Penetration Test Report – Comprehensive Network Security Analysis

This repository contains a pdf of my final project for the CIS4204 Penetration Testing and Ethical Hacking course at the University of Florida. 
The assignment was structured as a semester-long engagement where I acted as a security consultant for "Pr0b3 Security," tasked with conducting 
a penetration test of the fictitious client, "Arts Tailor Shoppe."

The project follows a professional penetration testing methodology, covering reconnaissance, exploitation, privilege escalation, lateral movement, 
and post-exploitation techniques. The report includes the following two sections:

Executive Summary: A high-level overview of the penetration test, security risks, and recommended mitigations.
Technical Report: A deep dive into findings, including vulnerability exploitation methods, confirmation steps, and remediation strategies.

Key Findings:
Zerologon Exploit (CVE-2020-1472): Gained domain controller access by exploiting cryptographic flaws in the Netlogon protocol.
Ease of Access Backdoor: Achieved SYSTEM-level access on a Windows machine through an unpatched Windows login screen vulnerability.
WPAD Poisoning & SSL Stripping: Intercepted credentials via man-in-the-middle attacks on misconfigured proxy authentication.
Password Spraying & Hard-Coded Credentials: Identified weak authentication policies and discovered hard-coded credentials in a mobile app backend.
Exploitable Buffer Overflow & VSFTPD Backdoor: Demonstrated remote code execution and privilege escalation through software vulnerabilities.

