# Task 1: Basic Network Scanning with Nmap

## Objective
The objective of this task is to perform a basic network scan using Nmap to identify open ports and services on a target machine.

## Tool Used
- Nmap (Network Mapper)

## Target
- IP Address: 10.129.49.248
- Environment: Authorized lab / virtual machine

## Scan Commands Used

nmap -sV --top-ports 20 -Pn 10.129.49.248
nmap -O -v 10.129.49.248




Findings
Open Ports

22/tcp (SSH): Secure Shell service running OpenSSH on Ubuntu.

80/tcp (HTTP): Apache web server running on Ubuntu.

OS Detection

Operating System: Linux (Kernel version 5.x)

Device Type: General purpose system

Significance of Open Ports

SSH (22): Allows remote administrative access. If misconfigured, it may be vulnerable to brute-force attacks.

HTTP (80): Hosts a web service. May expose web-based vulnerabilities if not properly secured.

Conclusion

The Nmap scan successfully identified active services and operating system details of the target machine. This information is useful for understanding the system’s attack surface and improving its security posture.

Disclaimer

This scan was performed on an authorized system for educational and internship purposes only.
