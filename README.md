# NetSentinel

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Python Version](https://img.shields.io/badge/python-3.8%2B-green)

A toolkit for network security professionals to scan, detect, and defend against network threats.

## Overview

NetSentinel demonstrates a practical implementation of defense-in-depth security principles. It provides tools for DNS reconnaissance, TCP scanning, and application-layer monitoring, following the complete security workflow from offensive reconnaissance to defensive countermeasures.

## Features

- **DNS Guardian**: DNS scanning and UDP flow monitoring tools
  - DNS enumeration using Scapy
  - DNS-based threat detection
  
- **TCP Gatekeeper**: TCP security and traffic control
  - Custom port scanner implementation
  - Firewall configuration templates
  
- **Application Bodyguard**: Application-layer security
  - HTTP request analysis
  - Traffic pattern detection

## Installation

```bash
# Clone the repository
git clone https://github.com/abbycakes02/security_scanning_proj.git

# Navigate to the project directory
cd security_scanning_proj

# Install dependencies
pip install -r requirements.txt

