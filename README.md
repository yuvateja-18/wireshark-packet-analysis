# wireshark-packet-analysis
This project demonstrates basic network traffic analysis using Wireshark. It includes a live packet capture (.pcap file) and a short report identifying key protocols such as DNS, TCP, and HTTP. The goal is to build hands-on skills in packet inspection, protocol filtering, and network troubleshooting. Ideal for cybersecurity beginners
# Wireshark Packet Capture Report

## Overview
Captured live traffic using Wireshark to identify common network protocols and analyze packet details.

## Protocols Identified
- *DNS*: Used for domain name resolution.
- *TCP*: Reliable transport protocol for web traffic.
- *HTTP*: Web browsing traffic.
- (Optional: Add UDP, TLS, ICMP if seen)

## Sample Packet Details
### DNS Query
- Source: 	10.76.159.154			
-DNS	87

- Destination:10.76.159.88
- Query:  A www.youtube.com

### TCP Handshake
- SYN → SYN-ACK → ACK
- Port: 443 (HTTPS)
TCP	66	53 → 1836 [SYN, ACK] 

### HTTP Request
- Method: GET


## Tools Used
- Wireshark 


## Outcome
Gained hands-on experience with packet capture, protocol filtering, and basic traffic analysis.
