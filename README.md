# Brute Force Attack Detection and Response with Wazuh

This repository showcases a multi-platform SOC simulation lab built using **Wazuh**, where brute-force attacks on both **Linux (SSH)** and **Windows (RDP)** are detected, visualized, and automatically blocked using **Active Response**.

---

## 🔐 Project Highlights

### 🔹 SSH Brute Force Detection & Response (Linux)
- Detected SSH brute-force attempts by monitoring `/var/log/auth.log` on Ubuntu client.
- Simulated attacks using **Hydra** and visualized them in the **Wazuh Dashboard**.
- Configured **Wazuh Active Response** (Rule ID: 5710) to block attacker IPs for 10 minutes.

📄 [View SSH Brute Force Report](1.Brute%20force%20log%20analysis.pdf)  
📄 [View Active Response Report](2.Response%20to%20brute%20force.pdf)

---

### 🔹 RDP Brute Force Detection & Response (Windows)
- Enabled Remote Desktop on a **Windows 11 Enterprise** client with Wazuh agent.
- Simulated **Hydra**-based RDP brute-force attacks from Kali Linux.
- Detected using Rule IDs `60122`, `60204` and blocked using **Active Response**.

📄 [View RDP Brute Force Report](3.Detection%20%26%20Response%20to%20RDP%20brute-force%20attack.pdf)

---

## 🛠️ Technologies Used
- **Wazuh** (SIEM + Active Response)
- **Ubuntu Linux** (Wazuh Server + Client)
- **Windows 11** (RDP Target with Agent)
- **Kali Linux** (Attack Simulation)
- **Hydra**, **OpenSSH**

---

## 🌐 Related Lab Setup Tutorials
- [Install Wazuh on Ubuntu Server](https://thecyberreactor.in/how-to-install-wazuh-on-ubuntu/)
- [Install Wazuh Agent on Ubuntu Client](https://thecyberreactor.in/how-to-install-the-wazuh-agent-on-an-ubuntu-client/)
- [Configure File Integrity Monitoring with Wazuh](https://thecyberreactor.in/how-to-configure-file-integrity-monitoring-with-wazuh/)

---

## 🎯 Skills Demonstrated
- Threat Detection (Linux + Windows)
- Active Defense and SIEM Configuration
- Log Monitoring and Rule-Based Response
- SOC Simulation and Multi-platform Hardening

> 🚨 This lab was built in a safe, controlled environment for educational and professional development purposes.

---

#️⃣ **#CyberSecurity #Wazuh #SIEM #SOC #BruteForce #LinuxSecurity #WindowsSecurity #ActiveResponse #Infosec #HandsOnSecurity**
