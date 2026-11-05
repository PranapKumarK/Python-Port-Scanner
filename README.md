# Python Port Scanner

A simple Python-based port scanner developed using socket programming. This tool scans a specified IP address within a user-defined port range and identifies open TCP ports.

## Features
- Accepts and validates an IPv4 or IPv6 address.
- Allows users to specify a port range.
- Scans ports using TCP socket connections.
- Identifies and displays open ports.
- Uses connection timeouts for scanning.

## Requirements
- Python 3.x
- No external libraries required.

## Usage

```bash
python3 port_scanner.py
```

Enter the target IP address and port range when prompted.

Example:
```text
Please enter the IP address that you want to scan: 127.0.0.1
Enter port range: 1-1024
```

## How It Works

The scanner attempts to establish TCP connections to each port within the specified range. If a connection succeeds, the port is identified as open.

## Disclaimer

This tool is intended for educational purposes and authorized network security testing only. Scan only systems you own or have explicit permission to test.
