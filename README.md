# soc-threat-detection-lab
SOC lab detecting SSH brute-force attacks using Splunk SIEM
##  Overview
This project demonstrates detection of SSH brute-force attacks using Splunk SIEM in a simulated SOC environment.

##  Lab Setup
- Kali Linux (Attacker)
- Ubuntu (Target)
- Splunk Enterprise
- VirtualBox

##  Steps Performed
- Collected Linux authentication logs
- Forwarded logs to Splunk
- Created SPL queries to detect failed login attempts
- Generated alerts for suspicious activity
- Simulated brute-force attack using Hydra from Kali Linux

##  Detection Logic
- Multiple failed login attempts from same IP
- Followed by successful login

##  Tools Used
Splunk, Kali Linux, Ubuntu, Wireshark, Nmap

##  Outcome
Successfully detected and analysed brute-force attacks using SIEM.

