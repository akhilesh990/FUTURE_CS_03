# FUTURE_CS_03

Cybersecurity Incident Analysis using Wireshark & Tshark

Overview
This repository contains the analysis steps and commands used to investigate a simulated cybersecurity incident using **Wireshark** and **Tshark** on Linux. The analysis focused on extracting and examining network traffic from a **PCAP file**.

Tools Used
- **Wireshark** (GUI-based network traffic analysis tool)
- **Tshark** (Command-line version of Wireshark)
- **Linux Terminal**

PCAP File Analysis Steps
1. Open PCAP File in Wireshark

2. Filter HTTP GET Requests

3. Extract Files from PCAP (If files were downloaded via HTTP)

4. Analyze DNS Requests for Suspicious Domains

5. Follow TCP Stream to Inspect Data
   

How to Reproduce the Analysis
1. Download the PCAP file from GitHub.
2. Open the PCAP file using Wireshark or Tshark.
3. Use the above commands to filter traffic, extract files, and analyze suspicious activity.
4. Document findings in an **incident response report**.
