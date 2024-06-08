Packet Sniffer with Scapy

Overview
This script is a simple packet sniffer built with Scapy in Python. It captures network packets on a specified interface, filters by protocol, and logs packet details to a file.

Prerequisites

Python 3.x
Scapy library (pip install scapy)

Usage

Run the script.

Enter the following parameters when prompted:

Network Interface (e.g., eth0)

Number of Packets to capture (0 for unlimited)

Capture Duration in seconds (0 for no timeout)

Protocol to filter by (arp, bootp, icmp, 0 for all)

Log File Name

Example

* Enter the interface on which to run the sniffer : eth0

* Enter the number of packets to capture : 10

* Enter the number of seconds to run the capture: 60

* Enter the protocol to filter by (arp|bootp|icmp|0 is all): icmp

* Please give a name to the log file: capture_log.txt

Features

Sets the network interface to promiscuous mode.

Captures and logs packet details including timestamp, protocol, source MAC, and destination MAC.
Supports filtering by specific protocols.

Notes

Permissions: May require administrative privileges.

Responsibility: Ensure you have permission to capture network traffic.

Disclaimer

Unauthorized packet sniffing can be illegal and unethical. Use responsibly.






