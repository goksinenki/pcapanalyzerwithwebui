# PCAP Analyzer PRO

![GitHub License](https://img.shields.io/badge/license-MIT-blue.svg)
![Python Version](https://img.shields.io/badge/python-3.10-green.svg)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=flat-square&logo=docker&logoColor=white)

Welcome to **PCAP Analyzer PRO**, a powerful and open-source network traffic analysis tool built with Python, Flask, and Scapy. This application allows users to upload PCAP files, analyze network protocols (TCP, HTTP, DNS, etc.), detect anomalies, and generate detailed reports. It is designed for network administrators, security researchers, and developers who need an efficient way to inspect packet captures.

## Features

- **Comprehensive Protocol Analysis**: Analyze TCP, HTTP, DNS, and TLS traffic.
- **Anomaly Detection**: Identify unanswered HTTP requests, failed DNS queries, and RFC violations.
- **Detailed Reporting**: Generate HTML-based visual reports and downloadable TXT summaries.
- **Expert Insights**: Highlight critical issues like abrupt RSTs, retransmissions, and zero-window conditions.
- **Docker Support**: Easily deployable via Docker containers.
- **Scalable Design**: Handles large PCAP files with efficient processing.

## Installation

### Prerequisites
- Python 3.10 or higher
- Docker (optional, for containerized deployment)

### Local Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/kullaniciadi/pcap-analyzer-pro.git
   cd pcap-analyzer-pro
