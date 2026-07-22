# network-design-and-traffic-analysis
Enterprise network design and traffic analysis using Cisco Packet Tracer and Wireshark, featuring subnetting, DHCP, routing, and HTTP/HTTPS packet analysis.
# Network Design and Traffic Analysis Using Cisco Packet Tracer and Wireshark

## Overview

This project demonstrates the design, configuration, and analysis of a small enterprise network using Cisco Packet Tracer and Wireshark. The network consists of three interconnected routers supporting separate Student, Staff, and Finance networks. The project includes IPv4 subnetting, DHCP configuration, router setup, network connectivity testing, and packet analysis of HTTP and HTTPS traffic.

Additionally, the project explores network security concepts by comparing unencrypted HTTP communication with encrypted HTTPS traffic, demonstrating how TLS protects sensitive information during transmission.

---

## Project Objectives

- Design a multi-router enterprise network
- Perform IPv4 subnetting for efficient IP address allocation
- Configure DHCP for automatic IP assignment
- Configure router interfaces and point-to-point links
- Test connectivity between network segments
- Capture and analyze HTTP traffic using Wireshark
- Analyze HTTPS traffic and the TLS handshake
- Understand the security differences between HTTP and HTTPS

---

## Technologies Used

- Cisco Packet Tracer
- Wireshark
- TCP/IP
- IPv4 Subnetting
- DHCP
- Routing
- HTTP
- HTTPS
- TLS
- Network Security

---

## Network Architecture

```text
                Router 1
                    │
      Student Network (DHCP)
                    │
              Point-to-Point
                    │
                Router 2
                    │
       Staff Network (DHCP)
                    │
              Point-to-Point
                    │
                Router 3
                    │
     Finance Network (DHCP)
```

---

## Project Structure

```text
network-design-and-traffic-analysis/
│
├── packet-tracer/
│   └── Enterprise_Network_Design.pkt
│
├── documentation/
│   └── Network_Design_and_Traffic_Analysis_Report.pdf
│
├── LICENSE
└── README.md
```

---

## Features

- Enterprise network topology using three routers
- IPv4 subnetting with optimized address allocation
- DHCP configuration for automatic IP assignment
- Router interface configuration
- Point-to-point router connectivity
- Network connectivity testing
- HTTP packet capture and analysis
- HTTPS packet analysis
- TLS handshake inspection
- Network security assessment

---

## Network Configuration

### Student Network

- Network Address: 192.168.0.0/29
- Default Gateway: 192.168.0.1
- DHCP Enabled

### Staff Network

- Network Address: 192.168.1.0/28
- Default Gateway: 192.168.1.1
- DHCP Enabled

### Finance Network

- Network Address: 192.168.2.0/28
- Default Gateway: 192.168.2.1
- DHCP Enabled

---

## Traffic Analysis

### HTTP Analysis

Using Wireshark, HTTP traffic was captured and inspected to demonstrate how login credentials are transmitted in plain text when encryption is not used. The analysis highlights the security risks associated with unencrypted communication.

### HTTPS Analysis

HTTPS traffic was analyzed by examining the TLS handshake between the client and server. The captured packets demonstrate how encryption is negotiated before secure communication begins, ensuring confidentiality and protecting transmitted data.

---

## Results

- Successfully designed and configured a multi-router enterprise network.
- Implemented IPv4 subnetting for efficient IP allocation.
- Configured DHCP services for automatic IP assignment.
- Verified network communication between configured subnets.
- Captured and analyzed HTTP traffic using Wireshark.
- Examined TLS handshake packets during HTTPS communication.
- Demonstrated the security advantages of HTTPS over HTTP.

---

## Skills Demonstrated

- Enterprise Network Design
- Cisco Packet Tracer
- Router Configuration
- IPv4 Addressing
- Subnetting
- DHCP Configuration
- Routing
- TCP/IP Networking
- Wireshark
- Packet Analysis
- HTTP
- HTTPS
- TLS
- Network Security
- Troubleshooting

---

## Future Improvements

- Configure dynamic routing protocols (OSPF or EIGRP)
- Implement VLANs for network segmentation
- Configure Access Control Lists (ACLs)
- Add firewall rules for enhanced security
- Deploy network monitoring and logging
- Expand the network with additional routers and services

---

## Documentation

The complete project documentation, including network design, subnetting calculations, router configuration, DHCP setup, packet analysis, testing results, and observations, is available in the `documentation` folder.

---

## Author

**Sakshi Teli**

