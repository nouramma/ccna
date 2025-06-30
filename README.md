---

# International School Network Project

## Project Overview

This project involves building and implementing a network infrastructure for an international school with two branches located 20 miles apart. The network supports staff and students across four buildings (A, B, C, and D) at the main branch, as well as the primary and KG sections at the smaller branch. The network design ensures effective communication, security, and management through VLAN segmentation, dynamic IP assignment, inter-VLAN routing, and other critical network services.



## Network Design and Components

1. **Topology**: 
   - The network uses a hierarchical topology where a core switch connects to distribution switches in each building. 
   - Fiber optic cables ensure high-speed communication between the buildings.

2. **IP Addressing & VLANs**:
   - Each department is assigned a private IP network with unique subnets.
   - VLANs are configured for each department to segment traffic and improve security.
     - VLAN 10: Management
     - VLAN 20: Admin
     - VLAN 30: Finance
     - VLAN 40: Student Affairs
     - VLAN 50: IT Department
     - VLAN 60: Labs
     - VLAN 70: Middle School
     - VLAN 80: High School
     - VLAN 90: Primary School
     - VLAN 100: KG School

3. **Routing**:
   - RIPv2 is used for internal routing within the main branch.
   - Static routing is implemented for external servers.

## Project Phases

### 1. Network Design 
- Designed the overall topology, IP addressing, and VLAN segmentation.
- Ensured each building is properly connected to the core switch using fiber optics.

### 2. Network Implementation 
- Installed and interconnected routers, core switch, and distribution switches.
- Connected end devices (PCs, printers, servers) and set up fiber connections.
- Configured inter-VLAN routing and switch port assignments.

### 3. Network Services Setup 
- Configured DHCP for dynamic IP assignment and DNS for hostname resolution.
- Set up the wireless network with WPA2/3 encryption and VLAN segmentation.
- Configured firewalls and ACLs to restrict inter-VLAN traffic for sensitive areas.

### 4. Network Management 
- Set up network monitoring tools (SNMP/NetFlow) and created automated alerts.
- Handled troubleshooting and documented network configurations.
- Created detailed network diagrams and a troubleshooting guide for future issues.

## Key Features
- **VLAN Segmentation**: Traffic is segmented between different departments for improved security and management.
- **DHCP & DNS**: Automatically assigns IP addresses and resolves internal hostnames.
- **Wi-Fi & Security**: Separate SSIDs for staff and students with WPA2/3 encryption.
- **Firewalls & ACLs**: Secure access control between VLANs and external networks.
- **Monitoring & Alerts**: Real-time performance monitoring and automated alerts for critical issues.

## Conclusion

The network is fully implemented and meets the requirements for efficient, secure, and reliable communication across both school branches. This project showcases our team's collaboration and expertise in designing, implementing, and managing a large-scale network.

## Future Improvements
- Expansion to include additional network services such as VoIP or video conferencing.
- Further optimization of wireless coverage and performance.

---
