# SOC Threat Detection Lab

## Project Overview
This project demonstrates a Security Operations Center (SOC) lab setup where I simulated and detected SSH brute-force attacks.

## Tools Used
- Kali Linux (Attacker)
- Ubuntu (Target)
- Splunk SIEM
- Hydra (Brute-force attack)
- Nmap (Network scanning)
- Wireshark (Packet analysis)

## Attack Simulation
- Performed SSH brute-force attack using Hydra from Kali Linux
- Targeted Ubuntu machine with weak credentials

## Detection and Analysis
- Monitored logs using Splunk SIEM
- Identified multiple failed login attempts
- Created search queries to detect brute-force patterns

## Key Learning
- Understanding of SOC workflow
- Log analysis and correlation
- Detection of brute-force attacks
- Hands-on experience with SIEM tools

## Future Improvements
- Add alerting rules in Splunk
- Automate detection
- Expand to other attack types
