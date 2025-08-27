# Day 1 – Home Lab Setup

## Overview
On the first day, I set up the core machines for my home lab:
- **Attacker:** Linux machine (Kali or similar)
- **Defender:** Windows 11 machine  
Both were used to test basic configurations and prepare for cybersecurity monitoring.

## Steps Completed
1. **Created Virtual Machines:**  
   - Linux attacker machine.  
   - Windows 11 defender machine.  
   ![Attacker and Defender Setup – Part 1](images/PART%201.png)  
   ![Attacker and Defender Setup – Part 2](images/PART%202png.png)  

2. **Internet Access and Tools:**  
   - Used **NAT networking** to temporarily connect both machines to the internet.  
   - Downloaded and installed **Splunk** and **Sysmon** for log collection and analysis.

3. **Securing the Environment:**  
   - Switched both machines to **Internal Adapter** so they were isolated from the host and internet.

4. **Static IP Assignment:**  
   - Assigned static IPs to both machines for consistent communication.  
   ![Windows Static IP](images/STATIC%20IP.png)  
   ![Linux Static IP](images/static%20IP%20LINUX.png)  

## Notes
This setup creates a safe isolated network to begin testing security tools. Future days will include log monitoring and attack simulations.
