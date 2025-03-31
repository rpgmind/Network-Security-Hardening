# Network-Security-Hardening
This project focuses on reducing the attack surface of a windows 10 virtual machine.  After identifying ports through a Nmap scan, then any unnecessary ports will be closed while ensuring that Remote Desktop Protocol (RDP) remains accessible in a controlled manner.  This uses concepts from my Security+ and Network+ certifications.

# Windows 10 Attack Surface Reduction Report

## Summary:
This report documents the process of closing unnecessary ports and restricting RDP access to reduce the attack surface of a Windows 10 VM.

## Steps Taken:
1. Identified open ports using Nmap.
2. Closed unnecessary ports (135, 139, 445, 5357) via Windows Firewall.
3. Restricted RDP access to a specific IP range.
4. Verified security improvements using Nmap scans.

## Findings:
- Previously open ports (135, 139, 445, 5357) were successfully closed.
- RDP access is now limited to a specific, trusted IP range.
- The Windows 10 VM is now more secure with reduced attack exposure.

## Conclusion:
This project reinforces security best practices related to network hardening, firewall management, and access control, demonstrating knowledge applicable to CompTIA Security+ and Network+ certifications.
