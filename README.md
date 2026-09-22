Cisco Enterprise Network

This is a Cisco Packet Tracer project that I created to practice enterprise networking.

What I Used

* VLANs
* DHCP
* OSPF
* Inter-VLAN Routing
* NAT
* ACL
* SSH
* Port Security

VLANs

| VLAN | Name       | Network       | Gateway    |
| ---- | ---------- | ------------- | ---------- |
| 10   | OPERATIONS | 10.10.10.0/24 | 10.10.10.1 |
| 20   | CREW       | 10.10.20.0/24 | 10.10.20.1 |
| 30   | GUEST      | 10.10.30.0/24 | 10.10.30.1 |
| 40   | IT         | 10.10.40.0/24 | 10.10.40.1 |
| 50   | SECURITY   | 10.10.50.0/24 | 10.10.50.1 |
| 99   | MANAGEMENT | 10.10.99.0/24 | 10.10.99.1 |

Network Devices

* R1-EDGE
* R2-CORE
* R3-CORE
* R4-ISP
* CORE-SW1
* CORE-SW2
* SW1-OPS
* SW2-CREW
* SW3-GUEST
* SW4-IT
* SW5-SECURITY
* SW6-MGMT
* PCs
* Internet Server

Main Features

VLAN

Different departments are separated into different VLANs.

DHCP

R2-CORE provides IP addresses to the PCs.

OSPF

OSPF is used between the routers for dynamic routing.

NAT

R1-EDGE provides NAT for internal users accessing the Internet.

Guest ACL

The Guest VLAN cannot access the internal VLANs, but it can access the Internet.

SSH

SSH is configured on the core switches for remote management.

Port Security

Access ports are protected using sticky MAC addresses and a maximum of one MAC address.

Testing

Some of the tests I performed:

* DHCP address assignment
* VLAN connectivity
* OSPF neighbor verification
* NAT translation
* Guest network isolation
* Internet connectivity
* SSH login
* Port security



Jericho Caliao
