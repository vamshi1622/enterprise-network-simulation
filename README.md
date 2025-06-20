# Enterprise Network Design & Simulation

This project simulates a multi-site enterprise network using GNS3. It includes VLAN segmentation, routing protocols, firewall zones, VPN connectivity, and infrastructure automation components — modeled on real-world enterprise architecture.


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

- **Simulation**: GNS3, VPCS
- **Design**: draw.io (topology diagrams)
- **Routing**: OSPF, EIGRP, RIP
- **Security**: Basic ACLs and VPN (simulated)
- **Docs**: Markdown, Visio/Canva (exports)

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

---

## 🧠 Next Steps

- Add voice VLANs and QoS simulation
- Integrate firewall objects (Fortinet, Palo Alto via EVE-NG)
- Expand automation with Ansible/Netmiko
