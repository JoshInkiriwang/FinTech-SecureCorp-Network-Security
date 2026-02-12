# FinTech SecureCorp: Enterprise Network Design & Security Validation

## Project Overview
This project presents the design and implementation of a secure network infrastructure for **"FinTech SecureCorp,"** a simulated financial technology environment. The project focuses on high-availability, logical segmentation, and robust security access controls to protect sensitive financial data in a FinTech ecosystem.

## My Roles & Responsibilities
In this collaborative graduate project, I served as the **Technical Lead for Documentation and Network Validation**, ensuring the project met professional standards and technical accuracy.

### 1. Technical Documentation & Refinement
- **Report Excellence:** Refined and restructured the overall project report (Chapter 1 to 5) to ensure professional academic standards.
- **Data Structuring:** Developed comprehensive IP addressing schemes and implementation tables (Chapter 4) for scalable network routing.

### 2. Network Design & Logical Validation
- **Logical Topology & Segmentation:** Designed and validated the logical structure and security segmentation using **Cisco Packet Tracer**.
- **Access Control Implementation:** Configured and tested **Standard & Extended ACLs** to secure internal segments and the Server Farm.
- **NAT Configuration:** Implemented Static NAT for secure public-facing services (Web Server).
- **Routing Strategy:** Verified the stability of **Static Routing** for this specific architectural requirement.

### 3. Simulation & Security Verification
- **Technical Validation:** Managed the transition from GNS3 to Cisco Packet Tracer to ensure functional delivery while maintaining core security features.
- **Evidence of Work:** Produced technical video recordings to demonstrate the network's resilience and functional integrity.

## Technical Highlights & Implementation
- **Hardware Optimization:** Utilized Layer 2/3 Switching modules on the main Firewall-Router to overcome physical port limitations via **SVI (Switch Virtual Interfaces)**.
- **Security Policy:** Implemented **ACL 110** with a 'Least Privilege' focus, strictly isolating the Server Farm from general staff access.
- **NAT & Public Access:** Configured Static NAT for HTTP/HTTPS traffic (Ports 80/443) to the Web Server.
- **Layer 2 Hardening:** Applied **Port-Security** on Internal LAN switches to mitigate unauthorized physical access.

## Repository Structure
- `Docs/`: Technical Report (PDF) and supporting documents.
- `Simulation/`: Validated Cisco Packet Tracer (.pkt) file.
- `Configurations/`: Clean CLI configuration scripts (.txt) for each device.
- `Assets/`: Network topology diagrams and addressing table screenshots.

## Future Work & Improvements
- **Service Redundancy:** Implementation of a dedicated DNS Server and Mail Server within the DMZ.
- **Advanced Security:** Integration of Intrusion Detection/Prevention Systems (IDS/IPS) and Honeypots.
- **Routing Scalability:** Migration from Static Routing to Dynamic Routing protocols (e.g., OSPF) for larger enterprise scalability.
- **Monitoring:** Implementation of SNMP-based network monitoring tools.

## Technologies Used
- **Network Simulation:** Cisco Packet Tracer
- **Security Protocols:** Access Control Lists (ACL), NAT, Port-Security
- **System Analysis:** Advanced Documentation & Requirement Validation
