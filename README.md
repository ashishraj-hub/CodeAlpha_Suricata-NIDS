# Network Intrusion Detection System (NIDS) using Suricata

## 📌 Project Overview
This project demonstrates the implementation of a **Network Intrusion Detection System (NIDS)** using **Suricata** on **Kali Linux**.  
The system monitors live network traffic and detects suspicious or malicious activities using custom detection rules.

---

## 🛠 Tools & Technologies
- Suricata
- Kali Linux
- Custom Suricata Rules
- Nmap (for attack simulation)

---

## 🔍 Features
- Real-time network traffic monitoring
- Detection of ICMP ping scans
- Detection of TCP SYN port scans
- Custom `local.rules` for intrusion detection
- Alert generation and logging

---

## ⚙️ How It Works
1. Suricata runs in IDS mode on a network interface.
2. Network packets are analyzed in real time.
3. Custom rules in `local.rules` match suspicious patterns.
4. Alerts are generated when a rule is triggered.

---

## 🧪 Testing & Validation
- ICMP scan tested using `ping`
- Port scan tested using `nmap -sS`
- Alerts verified in `/var/log/suricata/fast.log`

---

## 📂 Files Included
- `local.rules` – Custom Suricata detection rules
- `README.md` – Project documentation
- `screenshots/` – Proof of detection and alerts

---

## 🚀 Future Improvements
- Enable IPS mode for automatic blocking
- Integrate with ELK Stack for visualization
- Add alert automation scripts

---

## 👤 Author
**Ashish Raj**  

Cybersecurity Enthusiast | Network Security

