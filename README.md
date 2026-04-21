# Industrial Cybersecurity (OT/ICS)
**Rakibul Haque** | Minor in Industrial Cybersecurity @ Fontys University

Research and practical implementations focusing on the security of Operational Technology (OT) and Industrial Control Systems (ICS). This repository documents the transition from standard IT security to the specialized requirements of industrial environments.

---

## Technical Focus Areas

### 🏭 OT Infrastructure & Segmentation
- Implementation of the **Purdue Model** for industrial network hierarchy.
- Design of segmented zones (Cell, Area, Plant) using **Kathara** and Linux-based routing.
- Analysis of deterministic networking requirements and high-availability constraints.

### 🛡️ Industrial Defense
- Comparative analysis of IT vs. OT security priorities (Availability > Confidentiality).
- Hardening of Engineering Workstations (EWS) and Human-Machine Interfaces (HMI).
- Deep packet inspection of industrial protocols (Modbus, Profinet) via Wireshark.

### ⚙️ PLC Operations
- Logic design using **TIA Portal** (Ladder Diagram).
- Simulation of interlocking systems and motor control via PLCSim.
- Security constraints of legacy PLC firmware and lack of native encryption/authentication.

---

## Key Projects & Reports

### [Project 1: Network Segmentation for Industrial Zones](./network-labs/)
Detailed setup of isolated sensor, server, and operator networks to prevent lateral movement within a factory environment.

### [Project 2: IT vs OT Security Analysis](./reports/OT_vs_IT.pdf)
Comprehensive report on the unique attack surface of OT systems and why standard IT security patches can disrupt industrial operations.

---

## Toolchain
- **Simulation:** Kathara, Docker, PLCSim.
- **Engineering:** TIA Portal (Siemens).
- **Analysis:** Wireshark, tcpdump.

---
*All implementations were conducted in simulated environments to ensure safety and stability consistent with OT standards.*
