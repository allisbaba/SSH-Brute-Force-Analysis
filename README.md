# SSH Brute Force Attack Detection & Analysis

## 🛡️ Project Overview
This project demonstrates an end-to-end SOC analysis process. I simulated a targeted SSH Brute Force attack in a lab environment, analyzed the network traffic via Wireshark, and correlated system logs using Splunk SIEM.

## 🛠️ Tools & Technologies
- **SIEM:** Splunk Enterprise
- **Network Analysis:** Wireshark
- **Attack Tool:** Hydra
- **Environment:** VirtualBox (Kali Linux & Ubuntu)

## 📊 Key Findings
- **Targeted User:** `tier2one` (100% of attempts focused on this account)
- **Total Attempts:** 2047 failed login events detected.
- **Attacker IP:** 10.0.2.4 (Kali Linux)
- **Status:** **Inhibited.** No "Accepted Password" events found, confirming the attack failed.

## 📂 Repository Structure
- `/Evidence`: Contains the raw `.pcap` file and log samples.
- `/Report`: Full Incident Report in PDF format.
