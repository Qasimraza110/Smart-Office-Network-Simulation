# 🏢 Smart Office Network Simulation  

This project demonstrates the design and configuration of a **secure smart office network** with isolated departments, centralized services, and wireless access. It simulates a real-world organizational IT infrastructure with **VLANs, authentication, firewalls, and routing protocols** to ensure secure and structured connectivity.  

---

## 🎯 Objective  
- Build and configure a secure office network with **segmented departments**  
- Provide **wireless access** while maintaining security  
- Simulate **heterogeneous routing protocols** (e.g., RIP, OSPF) across routers  
- Apply **enterprise-grade security protocols** (802.1X, WPA2, Port Security, ACLs)  

---

## 📚 Theoretical Concepts  
- **VLANs** → Traffic isolation between departments  
- **Subnetting** → Structured IP address management  
- **802.1X** → LAN authentication for Admin Dept  
- **Port Security & MAC Filtering** → Restrict unauthorized device access  
- **NAT** → Secure outbound Internet communication  
- **Stateful Firewall + ACLs** → Protect internal servers  
- **WPA2 (AES)** → Secure wireless communication  

---

## 🛠️ Practical Setup  

| Block | Description                  | Devices |
|-------|------------------------------|---------|
| A     | Admin Dept (**802.1X**)      | 3 PCs   |
| B     | HR Dept (**VLAN 20, Port Security**) | 3 PCs   |
| C     | R&D Dept (**VLAN 30, MAC Filtering**) | 3 PCs   |
| D     | Server Room (**DNS, Web, Mail, Firewall**) | 3 Servers |
| E     | Wi-Fi Zone (**WPA2 Secured**) | 2 Laptops |

---

## 💻 Total Devices  
- **9 PCs**  
- **2 Laptops**  
- **2 Switches**  
- **1 Router**  
- **1 Wireless Router**  
- **3 Servers**  
- **1 ISP**  

---

## 🔐 Security Protocols Applied  

| Section | Protocol Applied |
|---------|------------------|
| Admin   | **802.1X Authentication** |
| HR      | **Port Security** |
| R&D     | **MAC Address Filtering** |
| Servers | **Stateful Firewall + ACLs** |
| Wi-Fi   | **WPA2 with AES Encryption** |

---

## ✅ Expected Outcomes  
- 🔒 **Secure wired & wireless connectivity**  
- 🚦 **VLAN-based communication restrictions**  
- 👨‍💻 **Authenticated device access**  
- 🌐 **Controlled Internet access via NAT & Firewall**  
- 🛡️ **Centralized protection for servers**  

---

## 📌 Tools / Platforms Used  
- Cisco Packet Tracer *  
- Network Devices: Routers, Switches, Access Points  
- Security Configurations: VLANs, ACLs, WPA2, Firewall  

---

⭐ *This project reflects a real-world enterprise IT environment with layered security and structured network design.*  
