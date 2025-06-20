# Enterprise Network Design & Simulation

This project simulates a multi-site enterprise network using GNS3. It includes VLAN segmentation, routing protocols, firewall zones, VPN connectivity, and infrastructure automation components — modeled on real-world enterprise architecture.

---

## 🌐 Topology Overview

- Headquarters (HQ) + 2 Branch Offices + Data Center
- VLANs per department (Sales, HR, IT) + Voice VLANs
- Routing Protocols: OSPF (HQ), EIGRP (Branch 1), RIP (Branch 2)
- Site-to-site VPN tunnels
- Firewall and security zones
- Internet access via HQ firewall
- Tools: GNS3, draw.io, VyOS, VPCS

---

## 🧱 Project Structure

| Folder       | Description                                      |
|--------------|--------------------------------------------------|
| `diagrams/`  | Network topology diagrams (Visio/draw.io)        |
| `configs/`   | Router/switch/firewall configuration files       |
| `scripts/`   | Automation (Python, Ansible) - optional          |
| `docs/`      | Design notes, addressing plans, test results     |

---

## ⚙️ Tools & Technologies Used

- **Network Simulation**: GNS3, Cisco IOS (or VyOS), VPCS  
- **Design & Documentation**: draw.io, Microsoft Visio, Canva, Confluence-style notes  
- **Routing Protocols**: OSPF, EIGRP, RIP, BGP (future lab)  
- **Switching Technologies**: VLANs, Inter-VLAN Routing, STP, EtherChannel  
- **Security**: Cisco ASA, pfSense/FortiGate (EVE-NG optional), ACLs, DMZ zones  
- **VPN**: IPsec Site-to-Site, GRE Tunnels, Remote Access VPN (Cisco AnyConnect or OpenVPN)  
- **Cloud Infrastructure (Planned Expansion)**: AWS VPC, Azure VNet (simulated routing)  
- **Monitoring & Analysis**: Wireshark, SolarWinds (demo), PRTG Network Monitor  
- **Automation (Future Phase)**: Ansible, Python (Netmiko), Git, REST APIs  
- **CI/CD & Version Control**: GitHub Actions, GitHub CLI (for automation pipelines)  
- **Operating Systems (Endpoints)**: Ubuntu, Windows 10 VMs (optional in GNS3 or VirtualBox)  

---

## 📄 What You’ll Find

- 📊 IP addressing plan and VLAN table  
- 📡 Routing configurations for each site  
- 🔐 VPN configuration (GRE/IPSec)  
- 📁 Real device configs and test logs  

---

## ✅ Learning Outcomes

- Designed an enterprise-grade network across multiple sites  
- Simulated real-world routing and segmentation scenarios  
- Practiced GNS3 simulations and topology documentation  
- Laid the groundwork for automation (future steps)  
- Integrated multi-vendor firewalls and endpoint monitoring  

---

## 🧠 Next Steps

- Add voice VLANs and QoS simulation  
- Integrate FortiGate firewall and Palo Alto (via EVE-NG)  
- Expand automation with Ansible, Python, and GitHub Actions 
