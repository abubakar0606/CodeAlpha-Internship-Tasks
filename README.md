**Network Sniffer**
**Overview**

This project is a Basic Network Sniffer developed in Python. It captures and analyzes live network traffic and displays important packet details in real time.
The tool uses the Scapy library for packet capturing and analysis on Windows systems with Npcap support.

**Features**

Captures network packets in real time.

Displays source and destination IP addresses.

Shows protocol type (TCP, UDP, ICMP).

Displays packet length, capture time, TTL, and flags.

Shows source and destination MAC addresses for Ethernet packets.

Supports fragmented IP packet analysis.

Provides TCP details such as sequence number, acknowledgment number, and TCP flags.

**Installation**
**Install required Python library:**


pip install scapy

**Install Npcap (for Windows):**

1. Visit the official Npcap website and download the installer.
2. Run the installer and complete the setup process.
3. Restart your system after installation.

**Usage
Navigate to the project directory:**


cd CodeAlpha_BasicNetworkSniffer

**Run the network sniffer script:**


python sniffer.py


**The program will start capturing live network packets and will display detailed information for each packet on the terminal in real time.**
