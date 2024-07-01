**Network Packet Analyzer**

**Overview**

This project involves developing a packet sniffer tool capable of capturing and analyzing network packets. The tool provides essential information such as source and destination IP addresses, protocols, and payload data. It is designed for educational purposes and to aid network administrators in monitoring network traffic for analysis and troubleshooting.

**Features**

- Packet Capture: Intercepts and logs network packets.
- Protocol Analysis: Identifies and categorizes packets by protocols such as TCP, UDP, ICMP, etc.
- IP Address Logging: Displays source and destination IP addresses for each packet.
- Payload Display: Extracts and shows the payload data from packets.

**Prerequisites**

Python 3.x

`scapy` library

`npcap` library

**Example Output**
```
Source IP: 192.168.1.10
Destination IP: 93.184.216.34
Protocol: 6
Source Port: 49560
Destination Port: 80
Payload: b'GET / HTTP/1.1\r\nHost: example.com\r\n\r\n'
==================================================
```
**Important Considerations**

1. Ethical Use: Ensure you have permission to capture packets on the network you are monitoring. Unauthorized packet sniffing can be illegal and unethical.
2. Performance: Sniffing packets can consume significant resources, especially on a busy network. Be mindful of the performance impact.

