# Hawkeye-Network-Forensics-Analysis
# Description
This project involves analyzing a PCAP file using Wireshark to detect malicious activity, identify data exfiltration, and reconstruct the attack timeline. The investigation simulates a real-world cyber incident involving a keylogger infection.

# Objectives
- Analyze network traffic using Wireshark  
- Identify suspicious domains and communications  
- Detect malware behavior  
- Extract sensitive data from packets  
- Reconstruct the attack timeline  

# Tools Used
- Wireshark  
- CyberChef  
- VirusTotal  
- IP Lookup Tools  

# Analysis & Key Findings
- Suspicious domain detected: `proforma-invoices.com`  
- Malicious file downloaded: `tkraw_Protected99.exe`  
- SMTP traffic revealed data exfiltration  
- Credentials found in plaintext via TCP stream  
- Malware identified as **HawkEye Keylogger**

# Attack Timeline
1. Victim accessed malicious domain  
2. Malware downloaded via HTTP  
3. Keylogger executed  
4. Credentials collected  
5. Data exfiltrated via SMTP  

# Indicators of Compromise (IOCs)
- Domain: proforma-invoices.com  
- Malware File: tkraw_Protected99.exe  
- Suspicious Email Activity  
- External IP communication  

# Learning Outcomes
- Network packet analysis  
- Malware detection via traffic  
- TCP stream analysis  
- Data extraction techniques  
- Attack reconstruction  

