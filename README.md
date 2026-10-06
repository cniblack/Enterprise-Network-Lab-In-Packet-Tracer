# Enterprise Network Lab

A simulated enterprise network built in Cisco Packet Tracer to practice
network design, routing, switching, DHCP, redundancy, and wireless
networking.

## Technologies

![Cisco Packet Tracer](https://img.shields.io/badge/-Cisco%20Packet%20Tracer-1BA0D7?&style=for-the-badge&logo=Cisco&logoColor=white)

- VLANs
- IPv4
- DHCP
- OSPF
- HSRP
- STP
- Inter-VLAN Routing
- Wireless LAN Controller (WLC)
- Access Points
- Firewalls
- Network Servers

## Network Topology

<img width="2539" height="1105" alt="image" src="https://github.com/user-attachments/assets/ccbfb223-1daa-49ad-bed2-ca24380490f0" />


## Project Overview

The goal of this project was to design and configure an enterprise
network using Cisco Packet Tracer.

The network was designed with multiple VLANs, dynamic routing, gateway
redundancy, DHCP services, wireless networking, and network security
components.

## Network Configuration

### VLANs

Created separate VLANs to segment network traffic and improve organization
and security.

| VLAN | Purpose |
|------|---------|
| VLAN 10 | Management |
| VLAN 20 | LAN |
| VLAN 30 | WLAN |
| VLAN 40 | VoIP |
| VLAN 199 | Disabled Ports |

### Routing

- Configured OSPF for dynamic routing between network devices.
- Configured inter-VLAN routing to allow communication between VLANs.
- Configured HSRP to provide default gateway redundancy.

### DHCP

-Configured DHCP to automatically assign IP addresses and network
configuration information to client devices.

### Switching

- Configured VLANs and trunk links.
- Configured EtherChannel to improve bandwidth and provide redundancy.
- Configured access ports for end devices.

### Wireless

- Configured a Wireless LAN Controller (WLC).
- Configured wireless access points.
- Connected wireless clients to the enterprise network.

### Security

- Configured firewall functionality within the simulated network.
- Implemented network segmentation using VLANs.
- Applied basic access and security controls to network devices.

## Troubleshooting

During the lab, I practiced troubleshooting:

- VLAN connectivity
- DHCP address assignment
- Routing issues
- Inter-VLAN communication
- HSRP gateway redundancy
- Wireless connectivity
- Device configuration errors

## Skills Demonstrated

- Network design
- Cisco IOS configuration
- Routing and switching
- VLAN configuration
- DHCP
- OSPF
- HSRP
- STP
- Wireless networking
- Network troubleshooting
- Enterprise network infrastructure

## Files

`enterprise-network-lab.pkt` - Complete Cisco Packet Tracer project.

The `configs` folder contains selected device configurations used in the
lab.
