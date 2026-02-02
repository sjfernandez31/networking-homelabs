# Lab 01 – VLAN Segmentation

## Objective
Configure multiple VLANs on a Layer 2 switch and verify that devices in different VLANs cannot communicate without routing.

## Tools Used
- Cisco Packet Tracer

## Network Topology
- 1 Cisco 2960 Switch
- 2 PCs
- Copper straight-through Ethernet cables

## IP Addressing Plan
| Device | VLAN | IP Address |
|------|------|-----------|
| PC1  | 10   | 192.168.10.10 |
| PC2  | 20   | 192.168.20.10 |

## Switch Configuration Summary
- VLAN 10 created and assigned to FastEthernet0/1
- VLAN 20 created and assigned to FastEthernet0/2
- No Layer 3 device configured

## Verification
- Ping from PC1 to PC2 fails as expected
- Confirms VLAN isolation on a Layer 2 switch

## What I Learned
- How VLANs logically segment a network
- How switch ports are assigned to VLANs
- Why inter-VLAN communication requires routing
