# Firewall-Rules
This project demonstrates the configuration and testing of basic firewall rules using Windows Firewall. The goal is to understand how firewalls filter network traffic and enforce security policies through port-based rules.

Introduction
This project demonstrates the configuration and testing of basic firewall rules using **Windows Firewall** and **UFW (Uncomplicated Firewall)** on Linux. The aim is to understand how firewalls filter traffic, manage access to services, and enhance system security.

---

 Steps Performed
1. Opened the firewall configuration tool:
   - Windows Firewall with Advanced Security
   - UFW terminal on Linux
2. Listed existing firewall rules.
3. Added a rule to **block inbound traffic on port 23 (Telnet)**.
4. Tested the rule using `telnet localhost 23`.
5. Added a rule to **allow SSH (port 22)** on Linux.
6. Removed the test block rule to restore the original state.
7. Documented commands, GUI steps, and outputs.
