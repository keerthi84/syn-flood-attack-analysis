# ⚡ SYN Flood Attack Simulation & Analysis

## 📌 Overview
This project demonstrates a **Denial of Service (DoS) attack using SYN Flood**, analysing its impact on system performance and evaluating mitigation techniques.

---

## 🛠️ Tools Used
- Kali Linux (Attacker)
- Windows (Target Machine)
- Hping3 (Attack Simulation)
- Wireshark (Packet Analysis)
- Nmap (Port Scanning)

---

## ⚙️ Methodology
1. Identify attacker and victim IP addresses
2. Verify connectivity using ping
3. Scan open ports using Nmap
4. Launch SYN flood using Hping3
5. Capture traffic using Wireshark
6. Analyse CPU, RTT, and bandwidth impact

---

## 💻 Attack Command
```bash
hping3 -V -S -p 135 --flood --rand-source <target-ip>
```

---

## 📊 Results & Analysis
- RTT increased significantly during attack
- CPU usage reached near 100%
- Bandwidth heavily consumed
- Network flooded with SYN packets

---

## 🛡️ Mitigation Techniques
- Rate Limiting
- SYN Proxy (more effective)
- Firewall filtering

---

## 📸 Screenshots
Replace placeholders in /screenshots with actual images from your report.

---

## 📄 Report
See full report in `report/SYN_Flood_Report.pdf`

---

## 👩‍💻 Author
Keerthi Krishnan
Cybersecurity Enthusiast
