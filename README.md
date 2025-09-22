Local Network Port Scan & Risk Analysis
Overview
This repository contains the results of a local network security assessment conducted using Nmap. The goal was to identify active devices, open ports, and potential vulnerabilities within the subnet `192.168.0.0/24`. The project was completed as part of an internship task focused on practical cybersecurity diagnostics.

Contents
- `nmap_scan1.txt`: Initial TCP SYN scan results with masked IPs and MAC addresses.
- `nmap_scan2.txt`: Follow-up scan confirming additional services (e.g., HTTPS, SSH).
- `Risk_analysis.txt`: Detailed breakdown of detected services, associated risks, and mitigation recommendations.

Privacy Considerations
- All IP addresses and MAC addresses have been anonymized or redacted.
- One device was intentionally excluded from the report due to privacy concerns.
- No packet captures or sensitive traffic data have been shared publicly.

 Key Findings
- Legacy services like FTP and Telnet were detected and flagged as high-risk.
- SMB ports (139/445) were identified as potential ransomware targets.
- Secure services (SSH, HTTPS) were confirmed in the second scan.
- UPnP was active on one device, warranting further review.

Tools Used
- Nmap 7.95 (`-sS` TCP SYN scan)
- Kali Linux terminal environment
- wireshark

Timeline
- Initial scan: September 22, 2025 – 19:31 IST
- Follow-up scan: September 22, 2025 – 20:40 IST
