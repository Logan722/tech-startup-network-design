# Tech Startup Network Design

Designing and simulating a secure tech startup network with VLAN segmentation, DMZ, and VPN access using Cisco Packet Tracer.

## Team
- Karrie Butcher
- Camryn McPhaul
- Daniel Opemipo Oni

## Repository Structure

```
├── deliverables/      # Checkpoint reports and project deliverables
├── presentations/     # Slide decks
├── media/             # Topology screenshots and visuals
├── docs/              # Additional documentation
└── README.md
```

## Project Overview

This project designs and simulates a secure network for a tech startup. The architecture uses a three-tier model (core, distribution, access) with department-level VLAN segmentation, a DMZ for public-facing servers, and a VPN gateway for remote employees.

### Key Features
- **Three-tier architecture** — Core, distribution, and access layers
- **VLAN segmentation** — Isolated broadcast domains for HR, Engineering, and Finance
- **DMZ** — Isolated web and email servers accessible from the internet
- **VPN gateway** — IPSec encrypted remote access for off-site employees
- **Perimeter firewall** — Cisco ASA 5505 with stateful packet inspection
- **Port security** — Sticky MAC address learning on all access-layer switches
