# Firewall and IDS Integration  

## 📌 Project Overview  
This project demonstrates the integration of a *Firewall (pfSense)* and an *Intrusion Detection System (IDS) using Snort, with monitoring and alerting powered by **Wazuh SIEM*.  
The goal is to enhance network security by combining firewall rules, intrusion detection, and centralized log management.  

---

## 🚀 Tools & Technologies  
- *pfSense* → Open-source firewall for network traffic filtering  
- *Snort* → Intrusion Detection System (IDS) for real-time traffic monitoring  
- *Wazuh* → SIEM for log analysis, threat detection, and alerts  
- *Ubuntu/Windows* → Endpoints for testing and integration  

---

## 🔧 Implementation Steps  
1. *Setup pfSense Firewall*
   - Installed pfSense on a VM  
   - Configured network interfaces (LAN, WAN)  
   - Applied firewall rules to filter traffic  

2. *Install & Configure Snort on pfSense*
   - Enabled Snort package  
   - Configured IDS rulesets (Emerging Threats, Snort VRT)  
   - Set Snort to detect malicious network activity  

3. *Integrate with Wazuh*
   - Installed Wazuh agent on pfSense  
   - Forwarded firewall and Snort logs to Wazuh Manager  
   - Verified alerts in Wazuh dashboard  

4. *Testing & Validation*
   - Simulated attacks (port scanning, suspicious traffic)  
   - Confirmed that pfSense blocked traffic and Snort generated alerts  
   - Wazuh received logs and triggered notifications  

---

## 📊 Results  
- Firewall successfully blocked unauthorized traffic  
- Snort detected intrusion attempts in real-time  
- Wazuh dashboard displayed centralized alerts  

---

## 📂 Repository Structure
