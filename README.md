# University Campus Network Simulation (Packet Tracer)

This repository contains an ongoing **university campus network simulation** built using **Cisco Packet Tracer**. The project represents a multi-building, multi-department academic network with a branch campus, simulating realistic campus LAN design and inter-campus connectivity.

---

## Project Overview

The network is designed for a hypothetical university (labeled *Albion Campus*), featuring:

- **Hierarchical Architecture:** Access → Distribution → Core → Cloud/ISP
- **Multi-Building Setup:** Multiple buildings and labs, connected via switches and a central router
- **Branch Campus:** Separate network block connected to main campus via serial and Gigabit links
- **Departmental VLANs:** Segmentation for Admin, HR, Finance, Business, IT, Student Labs, and more
- **Server Integration:** WEB, FTP, and EMAIL servers placed for simulated services
- **Subnetting:** Private IP addressing using 192.168.x.0/24 per VLAN

---

## Features & Highlights

| VLAN | Department/Area | Subnet (192.168.x.0/24) | Devices |
|------|----------------|------------------------|---------|
| 10   | Admin           | 192.168.1.0           | PCs + Printers |
| 20   | HR              | 192.168.2.0           | PCs + Printers |
| 30   | Finance?        | 192.168.3.0           | PCs + Printers |
| 40   | Business        | 192.168.4.0           | PCs + Printers |
| 50   | Building B/E&C  | 192.168.5.0           | PCs (Engineering & Computing) |
| 60   | Building C/A&D  | 192.168.7.0           | PCs (Arts & Design) |
| 70   | Student Lab     | 192.168.8.0           | PCs + Printers |
| 80   | IT Department   | 192.168.10.0          | PCs + Printers, Servers |

- **Trunk Links:** Inter-building connections use 802.1Q trunking (planned)
- **WAN/Cloud Connectivity:** Simulation of external connectivity via cloud router
- **Branch Link:** Albion Branch Campus connects back to main campus with serial and Gigabit links

---

## Current Status

- Topology and device placement mostly complete
- VLANs are labeled; basic cabling done
- Servers placed but services may not be fully configured
- Inter-VLAN routing, DHCP, routing protocols, and security configurations are pending

---

## Next Steps

1. Assign VLANs to access ports and configure trunk ports
2. Enable inter-VLAN routing (Router-on-a-Stick or Layer 3 switch)
3. Configure DHCP pools and routing protocols
4. Test end-to-end connectivity (PC → PC, PC → Server, Branch → Main)
5. Implement security measures (Port Security, ACLs, SSH)

---

## Learning Outcomes

- Designing hierarchical, multi-building campus networks
- Planning VLAN segmentation and subnetting for departments
- Understanding branch connectivity and WAN simulation
- Preparing for inter-VLAN routing and real-world network testing

---

## Screenshots / Diagrams

<img width="1426" height="900" alt="Screenshot 2026-01-29 at 09 25 55" src="https://github.com/user-attachments/assets/4b741abb-3545-4c6b-9c5d-312ad7d29763" />


- — Cisco Packet Tracer file for the campus network simulation

---

## Connect & Learn More

Check out my [LinkedIn post showcasing this project](https://www.linkedin.com/posts/onoghojebi-otaoghene-68a906380_networkingskills-techprojects-careerinit-activity-7422558888371240960-DHCj?utm_source=share&utm_medium=member_desktop&rcm=ACoAAF4bWEoBjoy2PP8NDcsPY8SRhgTeI0FOQUE) for more context and visual highlights.  

---

**Keywords:** Cisco, Packet Tracer, VLAN, Campus Network, Multi-Building, Inter-VLAN Routing, Branch Campus, Network Simulation, IT Infrastructure
