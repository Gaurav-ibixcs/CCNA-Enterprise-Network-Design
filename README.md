# 🔷 CCNA Enterprise Network Design & Implementation

## 📌 Project Overview
This project demonstrates an end-to-end enterprise network design for a mid-size organization using Cisco technologies.

## 🎯 Objectives
- Department-wise VLAN segmentation
- Inter-VLAN Routing (Router-on-a-Stick)
- Dynamic IP allocation using DHCP
- Secure routing using OSPF
- Internet access via NAT
- Traffic restriction using ACLs

## 🏢 Network Departments
| VLAN | Department | Network |
|-----|-----------|---------|
| 10 | HR | 192.168.10.0/24 |
| 20 | Finance | 192.168.20.0/24 |
| 30 | IT | 192.168.30.0/24 |

## 🧱 Technologies Used
- VLAN & Trunking
- Inter-VLAN Routing
- DHCP
- OSPF (Area 0)
- NAT (PAT)
- Extended ACLs

## 🔐 Security Implementation
- HR department blocked from accessing Finance Server
- ACL applied on router sub-interface

## 🛠 Tools Used
- Cisco Packet Tracer
- Cisco 2911 Routers
- Cisco 2960 Switches

## ✅ Verification
- `show vlan brief`
- `show ip route`
- `show ip ospf neighbor`
- `show ip nat translations`

## 📂 Files Included
- Packet Tracer (.pkt)
- Router & Switch configurations
- Network topology screenshots

## 🚀 Author
**Gaurav Butke**  
Junior Penetration Tester | Networking & Cybersecurity Enthusiast
