ARP Spoofing & HTTPS Downgrade Demo using Bettercap
For educational and penetration testing purposes only.

Description
This repository demonstrates how to perform an ARP Spoofing attack and capture network traffic using Bettercap in a controlled lab environment.
The goal is to showcase Man-in-the-Middle (MITM) concepts, ARP protocol vulnerabilities, and HTTPS downgrade techniques for cybersecurity learning.

⚠️ Disclaimer:
This project is intended only for use on networks you own or have explicit permission to test.
Unauthorized use of these techniques is illegal.

Key Concepts
ARP Spoofing: Sending forged ARP replies to associate the attacker’s MAC with the target’s IP.

MITM: Intercepting and relaying traffic between victim and gateway.

HTTPS Downgrade: Stripping HTTPS to capture unencrypted credentials/data.

Bettercap Caplets: Automating ARP spoofing and sniffing.

Tools Used
Kali Linux

Bettercap (MITM & packet capture)

Wireshark (optional for analysis)

Windows 10 VM (victim machine)

Lab Setup
Attacker Machine: Kali Linux

Victim Machine: Windows 10

Same LAN Network (e.g., 192.168.81.0/24)
