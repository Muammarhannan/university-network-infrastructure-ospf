# University Network Infrastructure Using Multi-Area OSPF

## Overview

This project demonstrates the design and implementation of a scalable campus network infrastructure using Cisco Packet Tracer.

The network integrates multiple departments through VLAN segmentation, Layer 3 Switching, and Multi-Area OSPF while providing centralized DHCP, DNS, and Web Services.

---

## Technologies

- VLAN
- Trunking
- Inter-VLAN Routing
- Layer 3 Switching
- Multi-Area OSPF
- DHCP
- DNS
- HTTP Web Services

---

## Network Scope

| Department | VLAN | Network |
|------------|------|----------|
| Faculty (FIT) | 10 | 192.168.10.0/24 |
| Directorate (DIR) | 20 | 192.168.20.0/24 |
| Library (LIB) | 30 | 192.168.30.0/24 |
| Data Center (DC) | 40 | 192.168.40.0/24 |
| Management | 99 | 192.168.99.0/24 |

---

## OSPF Design

| Area | Function |
|--------|----------|
| Area 0 | Backbone |
| Area 10 | Faculty |
| Area 20 | Directorate |
| Area 30 | Library |
| Area 40 | Data Center |

---

## Services

| Service | IP Address |
|----------|------------|
| DHCP Server | 192.168.40.10 |
| DNS Server | 192.168.40.11 |
| WEB Server | 192.168.40.12 |

---

## Project Features

- Dynamic Routing with OSPF
- VLAN Segmentation
- Inter-VLAN Communication
- Centralized DHCP Service
- Internal DNS Resolution
- Internal Web Hosting
- Hierarchical Network Design

---

## Validation

✔ DHCP Lease Acquisition

✔ DNS Name Resolution

✔ HTTP Web Access

✔ OSPF Neighbor Adjacency

✔ End-to-End Connectivity

---

## Author

Mu'ammar Hannan Najib

Network Engineer | IT Support | Cyber Security Enthusiast
