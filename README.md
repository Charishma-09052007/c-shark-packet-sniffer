# C-Shark Packet Sniffer

## Overview

C-Shark is a network packet sniffer and protocol analyzer developed in C using libpcap. The tool captures live network traffic, decodes packet headers, and provides detailed protocol-level analysis for monitoring and debugging network communication.

The project supports inspection of multiple network protocols and enables real-time packet analysis through a command-line interface.

## Features

### Packet Capture

* Live network traffic monitoring
* Packet capture using libpcap
* Real-time packet processing
* Network interface selection

### Protocol Analysis

* Ethernet Frame Analysis
* IPv4 Packet Parsing
* IPv6 Packet Parsing
* ARP Protocol Analysis
* TCP Segment Analysis
* UDP Datagram Analysis
* DNS Packet Inspection
* HTTP Traffic Analysis
* HTTPS Traffic Detection

### Traffic Monitoring

* Source and destination address tracking
* Port number analysis
* Protocol identification
* Packet statistics collection

### Filtering Support

* Protocol-based filtering
* Traffic inspection
* Targeted packet analysis

## Technologies Used

* C Programming
* libpcap
* Linux Networking APIs
* Socket Programming
* TCP/IP Protocol Stack

## System Architecture

```text
Network Interface
        │
        ▼
    libpcap
        │
        ▼
 Packet Capture Engine
        │
        ▼
 Protocol Decoder
        │
        ▼
 Traffic Analyzer
        │
        ▼
 Console Output
```

## Supported Protocols

### Layer 2

* Ethernet

### Layer 3

* IPv4
* IPv6
* ARP

### Layer 4

* TCP
* UDP

### Application Layer

* DNS
* HTTP
* HTTPS

## Key Concepts Implemented

* Packet Capture
* Network Traffic Analysis
* Protocol Parsing
* TCP/IP Networking
* Packet Inspection
* Systems Programming
* Network Monitoring
* Low-Level Data Processing

## Installation

### Install Dependencies

Ubuntu/Debian:

```bash
sudo apt-get install libpcap-dev
```

### Build Project

```bash
make
```

or

```bash
gcc *.c -o cshark -lpcap
```

## Usage

Run the packet sniffer:

```bash
sudo ./cshark
```

Select the desired network interface and begin monitoring traffic.

## Results

The project demonstrates low-level network packet capture and protocol analysis by decoding traffic across multiple layers of the TCP/IP stack. It provides insight into how network communication occurs between devices and services in real-world environments.

## Highlights

* Systems Programming Project
* Network Traffic Monitoring
* Protocol Analysis
* TCP/IP Stack Inspection
* libpcap Integration
* Real-Time Packet Capture
* Multi-Protocol Support
* Network Debugging Tool
