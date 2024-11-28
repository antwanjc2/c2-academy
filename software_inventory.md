# Software Installed on Network Devices

This document provides a detailed overview of the software installed on the various devices within the network.

## Device Overview

| Device Name      | Device Type            | IP Address       |
| ---------------- | ---------------------- | ---------------- |
| **OPNLion**       | Firewall (OPNsense)    | 192.168.56.110   |
| **WindowsLynx**   | Windows 11 Workstation | 192.168.56.111   |
| **WindowsTiger**  | Windows 2022 Server    | 192.168.56.112   |
| **UbuntuBobcat**  | Ubuntu 22.04 Server    | 192.168.56.113   |
| **UbuntuBadger**  | Ubuntu Workstation     | 192.168.56.114   |
| **MetaspoitableOwl** | Metaspoitable 2      | 192.168.56.115   |
| **KaliMammoth**   | Kali Linux             | DHCP Only        |

## Software Installed on Devices

### 1. **OPNLion** (Firewall - OPNsense)
   - **IP Address:** 192.168.56.110
   - **Software Installed:**
     - **Full Packet Capture**: Capture network traffic for analysis.
     - **IDS (Intrusion Detection System)**: Monitors network traffic for signs of suspicious activity.
     - **Firewall**: Manages incoming and outgoing network traffic.
     - **Captive Portal (LDAP Lab)**: Authentication portal for network users via LDAP.
     - **Zenarmor**: Advanced security solution for network traffic filtering.

### 2. **WindowsLynx** (Windows 11 Workstation)
   - **IP Address:** 192.168.56.111
   - **Software Installed:**
     - **Caldera Agent**: C2 (Command and Control) agent for red teaming exercises using MITRE ATT&CK framework.

### 3. **WindowsTiger** (Windows 2022 Server)
   - **IP Address:** 192.168.56.112
   - **Software Installed:**
     - **Active Directory**: A directory service that provides centralized management of users, groups, and resources on the network.

### 4. **UbuntuBobcat** (Ubuntu 22.04 Server)
   - **IP Address:** 192.168.56.113
   - **Software Installed:**
     - **Snort**: Open-source network intrusion detection and prevention system.
     - **Splunk**: Software platform for searching, monitoring, and analyzing machine-generated big data.
     - **Apache Directory Studio**: LDAP browser and directory client.
     - **LDAP**: Lightweight Directory Access Protocol implementation for directory services.

### 5. **UbuntuBadger** (Ubuntu Workstation)
   - **IP Address:** 192.168.56.114
   - **Software Installed:**
     - (No specific software listed, but it may include typical development and administrative tools).

### 6. **MetaspoitableOwl** (Metaspoitable 2)
   - **IP Address:** 192.168.56.115
   - **Software Installed:**
     - **Metaspoitable 2**: A vulnerable machine designed for penetration testing practice.

### 7. **KaliMammoth** (Kali Linux)
   - **IP Address:** DHCP Only
   - **Software Installed:**
     - Kali Linux tools: A penetration testing and security auditing suite.

## Summary

This document provides an overview of the software and services available on the devices within the network, ensuring transparency for system administrators, security analysts, and penetration testers.
