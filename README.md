# Corporate-Computer-Network-Design-and-Modeling

Project Overview

This project was developed as part of a Bachelor's Degree final project.

The objective of the project is to design and model a secure, scalable and manageable corporate computer network using Cisco Packet Tracer.

The network infrastructure includes VLAN segmentation, Inter-VLAN Routing, DHCP, DNS, VoIP telephony, wireless networking, network security mechanisms and Internet connectivity.

Software Environment

The project was designed and tested using:

Cisco Packet Tracer 9.x
GitHub
Microsoft Word

Compatibility

This project should be opened using Cisco Packet Tracer version 9.0 or newer.

Older Packet Tracer versions may not support all project features, devices and configurations.

Project file:

Corporate_Network.pkt

Project Objectives
Design a corporate network infrastructure
Implement VLAN segmentation
Configure Inter-VLAN Routing
Deploy DHCP and DNS services
Implement Cisco CME (VoIP)
Configure Staff and Guest Wi-Fi networks
Secure network administration using SSH
Implement Access Control Lists (ACL)
Configure NAT/PAT for Internet access
Provide scalability for future expansion
Organization Structure

The modeled corporate environment includes:

Department	Workstations:
Development	9
IT Support	6
Human Resources	2
Finance	2
Administration	2
Total	21

Additional Infrastructure
IP Phones	10
Network Printers	3
Wireless Access Points	2
DHCP/DNS Server	1
File Server	1
Network Devices
Device	Quantity
Cisco Catalyst 3560 (Layer 3 Switch)	1
Cisco Catalyst 2960 Switch	2
Cisco 2811 Router (Cisco CME)	1
ISP Router	1
DHCP/DNS Server	1
File Server	1
Wireless Access Point	2
Cisco IP Phone	10
Network Printer	4

Technologies Used:
VLAN Segmentation
Inter-VLAN Routing
EtherChannel
DHCP
DNS
VoIP (Cisco CME)
SSH
Access Control Lists (ACL)
NAT/PAT
Wireless Networking
VLAN Structure
VLAN ID	Purpose
10	Development
20	IT Support
30	HR
40	Finance
50	Administration
60	Voice
70	Servers
80	Guest WiFi
90	Staff WiFi
100	Printers
110	Management

Security Features:
Department-based VLAN segmentation
Management VLAN for network administration
SSH-only remote management
ACL-based Guest WiFi isolation
Access control for network devices
NAT/PAT for Internet connectivity
Scalability

The network architecture was designed with future expansion in mind.

Current infrastructure supports:

21 Workstations
10 IP Phones
3 Network Printers
2 Wireless Networks
Server Infrastructure

The design allows future growth to approximately 30–35 users with minimal infrastructure changes.
