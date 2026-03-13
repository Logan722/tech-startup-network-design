# tech-startup-network-design
Cisco Packet Tracer simulation of a secure tech startup network using a three-tier architecture with VLAN segmentation, DMZ, VPN, and firewall

# Tech Startup Network Design

## About

This is a team project for the Networking and Data Communications course at SMU. The goal is to design and simulate a secure network for a tech startup using Cisco Packet Tracer.

The network uses a three-tier architecture (core, distribution, and access layers) and includes VLAN segmentation across three departments, a DMZ for public-facing servers, VPN access for remote workers, and multiple layers of security.

## Network Overview

- **Core Layer** — Backbone of the network, connects all distribution-layer switches and ensures fast traffic forwarding between segments.
- **Distribution Layer** — Handles routing between VLANs and enforces policies controlling inter-department communication.
- **Access Layer** — Connects end-user devices across three department VLANs: HR, Engineering, and Finance.
- **DMZ** — Hosts the web server and email server, accessible from the internet without exposing the internal network.
- **Remote Access** — VPN gateway allowing off-site employees to securely connect to internal resources.

## Security Features

- Firewall between the internal network, DMZ, and the internet
- VLAN segmentation separating HR, Engineering, and Finance
- ACLs on distribution-layer switches to restrict inter-VLAN traffic
- VPN gateway with encrypted connections and identity verification
- Port security on access-layer switches to block unknown devices

## Tools

- Cisco Packet Tracer

## Repository Structure

```
├── docs/              # Checkpoint PDF, final report, and written deliverables
├── packet-tracer/     # .pkt simulation files
├── screenshots/       # Physical view and other network visuals
├── presentation/      # Video link and any related materials
└── README.md
```

## Team

- [Team Member 1] — Topic, Motivation, Overall Plan
- [Team Member 2] — Number of Major Areas, Security Measures
- [Team Member 3] — Type and Number of Devices, Packet Tracer Screenshot
