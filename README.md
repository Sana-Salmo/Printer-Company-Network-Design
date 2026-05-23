
# Printer Company Network Design using Cisco Packet Tracer

This project presents a network design for a printer company with one headquarters located in Jeddah and two branches located in Makkah and Madinah. The headquarters includes four departments: IT, HR, Accounting, and Sales, in addition to a DHCP server room.

Each department in the headquarters was separated using its own VLAN to organize the network and improve isolation between departments. The end devices receive their IP addresses automatically from the DHCP server. The branches are connected to the headquarters using routers, and RIP routing is used to allow communication between different locations.

## Key Details

- **Course:** CS2091 / Computer Networks
- **Tool:** Cisco Packet Tracer
- **Organization:** Printer company
- **Headquarters Location:** Jeddah
- **Branches:** Makkah and Madinah
- **Departments:** IT, HR, Accounting, Sales
- **End Devices:** PCs and printers
- **Intermediate Devices:** Routers, switches, and multilayer switch
- **Network Features:** VLANs, DHCP, routing, branch connectivity
- **Routing Protocol:** RIP
- **Testing Method:** Ping between PCs in different networks
- **Main Goal:** Build a connected company network that allows communication between departments and branches

## Network Structure

The headquarters contains four departments and a DHCP server room:

- IT department: 4 PCs and 1 printer
- HR department: 4 PCs and 1 printer
- Accounting department: 4 PCs and 1 printer
- Sales department: 5 PCs and 2 printers
- DHCP server room

Each department is configured in a separate VLAN. The switches are connected through a multilayer switch, and the multilayer switch is connected to a router for communication with the branches.

The Makkah and Madinah branches each include a sales department and are connected to the headquarters through routers.

## Main Network Features

- VLAN configuration for department isolation
- DHCP configuration for automatic IP address assignment
- Multilayer switch configuration for inter-VLAN communication
- Router configuration for branch connectivity
- RIP routing protocol for routing between routers
- Ping testing to verify network connectivity

## Connectivity Testing

The network was tested using ping messages between different locations, including:

- From a PC in the Madinah branch to a PC in the Jeddah headquarters Accounting department
- From a PC in the Makkah branch to a PC in the Madinah branch
- From a PC in the IT department to a PC in the Sales department inside the Jeddah headquarters

The successful ping results confirm that the network was configured correctly and that communication between departments and branches works as expected.

## Files Included

- `computer network project.pkt` — Cisco Packet Tracer project file.
- `FinalProject_CS2091_Spring2024-Summary.docx` — Final project summary report with network description and screenshots.

## Project Scope

This project demonstrates the design and configuration of a company network using Cisco Packet Tracer. It focuses on VLAN-based department separation, DHCP-based IP assignment, branch-to-headquarters connectivity, and routing between different network locations.

## Authors

Sana Rahmani 
Esraa Basalamh   
Rama Alkusair  

Effat University – CS2091 Computer Networks
