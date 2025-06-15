# 📡 FBE Campus Network Design – Cisco Packet Tracer

This project presents a comprehensive **logical network design** for the _Faculty of Business and Economics (FBE)_ using **Cisco Packet Tracer**. The setup includes multiple VLANs, IP addressing, trunk links, and Layer 3 configurations for efficient segmentation and communication.

---

## 🌐 Services & IP Addressing

| 🔧 Service | 🌍 IP Address |
|-----------:|:-------------|
| 📁 FTP     | `10.9.23.2`  |
| 🌐 Web     | `10.9.23.3`  |
| 📧 Mail    | `10.9.23.4`  |
| 🧭 DNS     | `10.9.23.5`  |

---

## 🛠️ VLAN Configuration

A total of **12 VLANs** were configured for logical segmentation across departments:

| VLAN ID | Department         |
|--------:|--------------------|
| 10      | 🖥️ Server Farm     |
| 20      | 📚 Library         |
| 30      | 🏢 Men's Dorm       |
| 40      | 🏠 Women's Dorm     |
| 50      | 👩‍🎓 Ladies Library  |
| 60      | 🧑‍💼 Student Service |
| 70      | 🧑‍💼 Management       |
| 80      | 💼 Economics        |
| 90      | 📊 Accounting       |
| 100     | 🏢 Admin Office     |
| 110     | 🎤 Auditorium       |
| 120     | 🧑‍🏫 Eshetu Chole    |

---

## ⚙️ Key Network Configurations

- ✅ **VLANs Created & Named** via CLI
- 🔌 **Access Ports Assigned** according to device placement
- 🔀 **Trunk Links Set** between switches for VLAN propagation
- 🌐 **SVIs Configured** on Layer 3 switch for inter-VLAN routing
- 💾 **Saved Configurations** using `write memory`

---

## 🧾 Notes

- 📡 **Inter-VLAN Routing** is handled through **Layer 3 Switch SVIs**
- 🔗 **Trunk Port** (`GigabitEthernet0/0`) allows VLANs: `10-120`
- 🧪 **Testing:** Use `ping` to verify connectivity across VLANs

---

## 📁 File Info

- `fbe-campus.pkt` – Cisco Packet Tracer project file
- `README.md` – Project description and documentation

> Designed and documented with clarity to simulate a real-world campus network infrastructure 🌍
