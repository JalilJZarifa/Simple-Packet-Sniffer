# Simple-Packet-Sniffer

This packet sniffer is a network monitoring tool designed to capture and display TCP and UDP packet information on a network interface. It's built using Python with the Scapy library.

Features
TCP and UDP Packet Capturing: Captures and displays source and destination IP addresses and port numbers.
HTTP Traffic Filtering: Includes an option to filter and capture only HTTP traffic (TCP port 80).
Easy-to-Read Output: Displays packet information in a clear, readable format.

# Prerequisites
Python 3.x
Scapy library
WinPcap or Npcap (for Windows users)
Root or Administrator access (for capturing packets)

# Installation
Install Python: Ensure Python 3.x is installed on your system.
Install Scapy: Run pip install scapy to install the Scapy library.
Install Npcap (Windows): Download and install Npcap for Windows. During installation, select "Install Npcap in WinPcap API-compatible mode."

# Usage
Clone the Repository:
git clone https://github.com/JalilJZarifa/packet-sniffer.git
cd packet-sniffer

Run the Sniffer:
To capture all TCP and UDP packets:
python packet_sniffer.py

To capture only HTTP traffic (TCP port 80):
python packet_sniffer.py --http

View the Output:
The script will output packet details to the console in real-time.
Press Ctrl+C to stop the packet capture.

# Output Format
The tool outputs each packet's source IP, source port, destination IP, and destination port. Example:
TCP Packet: 192.168.1.100:1030 -> 93.184.216.34:80
UDP Packet: 192.168.1.100:1053 -> 8.8.8.8:53

# Contributing
Contributions to this project are welcome. Please fork the repository and submit a pull request with your changes.
