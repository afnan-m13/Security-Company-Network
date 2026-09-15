# 🛡️ Security Company Network

A complete Cisco Packet Tracer simulation of a multi-department enterprise network architecture for an operational security firm.

---

### 📷 Network Topology Diagram

<img width="1198" height="571" alt="network" src="https://github.com/user-attachments/assets/d3b47aae-270f-4c4b-b4af-b245c7237433" />

---

### 📌 Project Overview
* **Core Routing**: 3x Cisco 1841 Routers configured with **RIP**
* **Infrastructure**: 6 segregated Local Area Networks (LANs)

---

### ⚡ Key Network Services
* **Dynamic Addressing**: Localized DHCP server per department (`.101`).
* **DNS Resolution**: Centralized server at `192.168.0.103`.
* **Hosted Web Domains**: Hosts `securitycompany.com`, `cisco.com`, `email.com`, and `banner.com`.
* **VoIP Telephony**: IP phones configured across departmental subnets.

---

### 🌐 Network Addressing Scheme

| LAN / Department | Network IP | Default Gateway | DHCP IP | End Devices |
| :--- | :--- | :--- | :--- | :--- |
| **Server Room** | `192.168.0.0/24` | `192.168.0.100` | `192.168.0.101` | 1 PC, DNS Server, 4 Web Servers |
| **Computer Dept.** | `192.168.1.0/24` | `192.168.1.100` | `192.168.1.101` | 3 PCs, 1 Printer, 1 IP Phone |
| **Internet Lab** | `192.168.2.0/24` | `192.168.2.100` | `192.168.2.101` | 3 PCs, 1 Printer, 1 IP Phone |
| **IT Department** | `192.168.3.0/24` | `192.168.3.100` | `192.168.3.101` | 3 PCs, 1 Printer, 1 IP Phone |
| **Manager Office** | `192.168.4.0/24` | `192.168.4.100` | `192.168.4.101` | 2 PCs, 1 Laptop, 1 Printer, 1 IP Phone |
| **Call Center** | `192.168.5.0/24` | `192.168.5.100` | `192.168.5.101` | 2 PCs, 2 Printers, 1 IP Phone |

---

### 🚀 Quick Test
1. Open the `.pkt` file in **Cisco Packet Tracer**.
2. Ping across subnets to verify **RIP routing**.
3. Navigate to `securitycompany.com` on any client browser to verify **DNS & Web services**.

---

### 👥 Team
* **Authors**: Jana Mufti, Afnan Kamel, Aya Mohammed, Afrah Bashaddadah
* **Supervisor**: Dr. Mohammad Nauman
* **Course**: Computer Networks (CS2091)

