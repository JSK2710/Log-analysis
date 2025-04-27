# Brute Force Attack Detection and Response using Wazuh

This repository showcases a two-part project focused on detecting and responding to brute-force SSH login attempts using **Wazuh**.  
It demonstrates both **log analysis** for identifying attacks and **active response** for automatically blocking malicious IPs.

---

## 📚 Project Parts

### 1. Brute Force Log Analysis using Wazuh
- Configured Wazuh agent to monitor `/var/log/auth.log` for failed SSH login attempts.
- Set up an SSH server on the client machine.
- Simulated brute-force attacks using **Hydra** from a Kali Linux attacker machine.
- Detected suspicious activity using Wazuh and visualized alerts in the Threat Hunting dashboard.

🔗 [View Documentation](1.Brute%20force%20log%20analysis.pdf)

---

### 2. Response to Brute Force Attack with Wazuh Active Response
- Configured **Wazuh Active Response** to trigger a **firewall-drop** when a brute-force attack is detected (Rule ID: 5710).
- Automatically blocked attacker IPs for **10 minutes** after multiple failed SSH login attempts.
- Simulated the attack again and successfully verified that active response blocked further SSH login attempts.
- Alerts and response events were visualized in the Wazuh Dashboard.

🔗 [View Documentation](2.Response%20to%20brute%20force.pdf)

---

## 🛠️ Tools and Technologies
- **Wazuh** (SIEM and Active Response)
- **Ubuntu Linux** (Wazuh Server and Client)
- **Kali Linux** (Attacker Machine)
- **Hydra** (Brute-force attack tool)
- **OpenSSH** (SSH Server)

---

## 🚀 Skills Developed
- Log Monitoring and Threat Detection
- Security Automation using Active Response
- Brute Force Attack Simulation
- SIEM Tools Integration
- Linux System Administration
- Threat Hunting and Incident Response

---
