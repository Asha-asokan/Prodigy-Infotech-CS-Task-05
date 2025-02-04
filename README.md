# Prodigy-Infotech-CS-Task-05

# Network Packet Analyzer

# Project Description
The Network Packet Analyzer is a Python-based tool designed to capture, inspect, and analyze network packets in real-time. It is built using the Scapy library, which provides powerful capabilities for low-level packet manipulation. This tool is useful for understanding network communication, troubleshooting, and exploring cybersecurity concepts.
The project emphasizes ethical usage and is intended for educational purposes, enabling users to gain hands-on experience in analyzing network traffic without violating privacy or legal boundaries.

# Key Features
- Real-Time Packet Capturing:
Captures live network packets from a specified or default network interface.

- Comprehensive Packet Analysis:
Extracts and displays detailed packet information, including:
Source and Destination IP Addresses: Tracks communication endpoints.
Transport Layer Protocols: Identifies whether the packet uses TCP, UDP, or others.
Ports: Displays source and destination port numbers for TCP/UDP packets.
Payload Analysis: Shows raw payload data in both hexadecimal and ASCII formats.

- Cross-Protocol Support:
Supports IP-based packets, including TCP, UDP, and raw data payloads.

- Customizable Interface:
Allows the user to specify the network interface to capture traffic from (e.g., Wi-Fi, Ethernet).

- User-Friendly Output:
Presents captured data in a structured and readable format.

- Lightweight and Efficient:
Built using Python, ensuring portability and simplicity.

- Ethical Usage:
Designed strictly for educational purposes, promoting responsible and legal usage.

# Key Components of the Code

- Packet Sniffing:
The sniff() function from Scapy captures live traffic and passes packets to the packet_callback() function for processing.

- Protocol and Port Analysis:
Identifies whether the packet belongs to TCP or UDP and extracts the corresponding source and destination ports.

- Payload Decoding:
Converts raw payload data into human-readable formats:
Hexadecimal: For detailed byte-level inspection.
ASCII: For text-based interpretation, ignoring decoding errors.
