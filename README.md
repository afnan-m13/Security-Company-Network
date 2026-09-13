# 🛡️ Security Company Network

A complete Cisco Packet Tracer simulation of a multi-department enterprise network architecture for an operational security firm[cite: 4].

---

### 📷 Network Topology Diagram

![Security Company Network Topology]
<img width="1198" height="571" alt="network" src="https://github.com/user-attachments/assets/d3b47aae-270f-4c4b-b4af-b245c7237433" />



---

### 📌 Project Overview
* **Contributors**: Jana Mufti, Afnan Kamel, Aya Mohammed, Afrah Bashaddadah[cite: 4]
* **Supervisor**: Dr. Mohammad Nauman[cite: 4]
* **Core Routing**: 3x Cisco 1841 Routers configured with **RIP**[cite: 4]
* **Infrastructure**: 6 segregated Local Area Networks (LANs)[cite: 4]

---

### ⚡ Key Network Services
* **Dynamic Addressing**: Localized DHCP server per department (`.101`)[cite: 4].
* **DNS Resolution**: Centralized server at `192.168.0.103`[cite: 4].
* **Hosted Web Domains**: Hosts `securitycompany.com`, `cisco.com`, `email.com`, and `banner.com`[cite: 4].
* **VoIP Telephony**: IP phones configured across departmental subnets[cite: 4].

---

### 🌐 Network Addressing Scheme

| LAN / Department | Network IP | Default Gateway | DHCP IP | End Devices |
| :--- | :--- | :--- | :--- | :--- |
| **Server Room** | `192.168.0.0/24` | `192.168.0.100`[cite: 4] | `192.168.0.101`[cite: 4] | 1 PC, DNS Server, 4 Web Servers[cite: 4] |
| **Computer Dept.** | `192.168.1.0/24` | `192.168.1.100`[cite: 4] | `192.168.1.101`[cite: 4] | 3 PCs, 1 Printer, 1 IP Phone[cite: 4] |
| **Internet Lab** | `192.168.2.0/24` | `192.168.2.100`[cite: 4] | `192.168.2.101`[cite: 4] | 3 PCs, 1 Printer, 1 IP Phone[cite: 4] |
| **IT Department** | `192.168.3.0/24` | `192.168.3.100`[cite: 4] | `192.168.3.101`[cite: 4] | 3 PCs, 1 Printer, 1 IP Phone[cite: 4] |
| **Manager Office** | `192.168.4.0/24` | `192.168.4.100`[cite: 4] | `192.168.4.101`[cite: 4] | 2 PCs, 1 Laptop, 1 Printer, 1 IP Phone[cite: 4] |
| **Call Center** | `192.168.5.0/24` | `192.168.5.100`[cite: 4] | `192.168.5.101`[cite: 4] | 2 PCs, 2 Printers, 1 IP Phone[cite: 4] |

---

### 🚀 Quick Test
1. Open the `.pkt` file in **Cisco Packet Tracer**[cite: 4].
2. Ping across subnets to verify **RIP routing**[cite: 4].
3. Navigate to `securitycompany.com` on any client browser to verify **DNS & Web services**[cite: 4].
