# 24-Node-LAN-Network-Design-Using-VLSM

## Project Overview
This project demonstrates the implementation of a Local Area Network (LAN) topology in the Huawei eNSP simulator using a 24-port network switch connected with 24 PCs.

The project includes:
- Network topology creation in eNSP
- Connection of 24 PCs to a 24-port switch
- IP address assignment using VLSM
- Device labeling/captioning
- Basic LAN communication setup

---

## Software Used
- Huawei eNSP
- Windows Operating System

---

## Network Topology
- 1 × 24-Port Switch
- 24 × PCs
- Star Topology

---

## IP Addressing Scheme

### Subnet Information
- Network Address: `10.0.0.0`
- Subnet Mask: `255.255.255.224`
- CIDR Notation: `/27`

---

## PC Configuration Table

| PC Name | MAC Address | IP Address |
|---|---|---|
| PC-1 | 54-89-98-5B-02-4D | 10.0.0.1 |
| PC-2 | 54-89-98-CB-34-80 | 10.0.0.2 |
| PC-3 | 54-89-98-91-13-D7 | 10.0.0.3 |
| PC-4 | 54-89-98-E0-02-EB | 10.0.0.4 |
| PC-5 | 54-89-98-55-7E-68 | 10.0.0.5 |
| PC-6 | 54-89-98-B4-36-2A | 10.0.0.6 |
| PC-7 | 54-89-98-ED-29-58 | 10.0.0.7 |
| PC-8 | 54-89-98-C2-3B-4B | 10.0.0.8 |
| PC-9 | 54-89-98-8E-62-8D | 10.0.0.9 |
| PC-10 | 54-89-98-2D-60-38 | 10.0.0.10 |
| PC-11 | 54-89-98-42-0F-E7 | 10.0.0.11 |
| PC-12 | 54-89-98-5B-68-DA | 10.0.0.12 |
| PC-13 | 54-89-98-34-4E-52 | 10.0.0.13 |
| PC-14 | 54-89-98-40-20-4A | 10.0.0.14 |
| PC-15 | 54-89-98-D9-5E-6B | 10.0.0.15 |
| PC-16 | 54-89-98-9B-64-92 | 10.0.0.16 |
| PC-17 | 54-89-98-E6-33-9F | 10.0.0.17 |
| PC-18 | 54-89-98-1C-46-88 | 10.0.0.18 |
| PC-19 | 54-89-98-2F-17-CD | 10.0.0.19 |
| PC-20 | 54-89-98-42-67-12 | 10.0.0.20 |
| PC-21 | 54-89-98-45-0E-2B | 10.0.0.21 |
| PC-22 | 54-89-98-9B-71-CC | 10.0.0.22 |
| PC-23 | 54-89-98-F5-73-75 | 10.0.0.23 |
| PC-24 | 54-89-98-60-27-D6 | 10.0.0.24 |

---

## Steps Performed
1. Added a 24-port switch in eNSP.
2. Connected all 24 PCs to the switch using Ethernet cables.
3. Assigned static IP addresses to each PC.
4. Configured subnet mask `255.255.255.224`.
5. Inserted labels/captions for all devices.
6. Verified network connectivity using ping commands.

---

## Objectives
- Understand LAN topology design
- Learn IP addressing using VLSM
- Practice network simulation using eNSP
- Understand switch-based communication

---
