# networking-labs
networking-labs/
│
├── vlan-configuration/
# VLAN Configuration Lab

## Overview
This lab demonstrates how to configure VLANs on Cisco switches to improve network segmentation and communication management.

## Technologies Used
- Cisco Packet Tracer
- VLANs
- Trunk Ports
- Access Ports

## Objectives
- Create VLANs
- Assign switch ports to VLANs
- Configure trunking between switches
- Verify VLAN connectivity

## Commands Used
```bash
enable
configure terminal
vlan 10
name SALES
interface fa0/1
switchport mode access
switchport access vlan 10
├── subnetting-practice/
├── ospf-lab/
├── static-routing/
└── README.md
