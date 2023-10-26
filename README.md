# Network_Scanner

The Network Scanner is a simple Python script that allows you to scan your local network and identify connected devices.

## Prerequisites

Before using the Network Scanner, make sure you have the following prerequisites installed:

- [Python](https://www.python.org/downloads/) (version 3.x)
- [Scapy](https://scapy.readthedocs.io/en/latest/installation.html)

You can install Scapy using the following command:

```bash
pip install scapy

Usage
Clone the repository:
git clone https://github.com/yourusername/network-scanner.git

Run the script:
python CheckmyNetwork.py

The script will prompt you to enter the IP range to scan (e.g., 192.168.1.1/24). It will then display a list of devices on the network along with their IP addresses and MAC addresses.

Example
IP Address         MAC Address
-----------------------------------------
192.168.1.1        00:1a:2b:3c:4d:5e
192.168.1.10       01:2a:3b:4c:5d:6e
...
Customization
You can customize the script by modifying the ip_range variable in the network_scanner.py file. Adjust the IP range based on your network configuration.

Contributing
If you'd like to contribute to the project, feel free to open an issue or submit a pull request. Contributions are always welcome!
