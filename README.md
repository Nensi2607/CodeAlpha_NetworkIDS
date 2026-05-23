# 🚨 Network Intrusion Detection System using Snort

## 📌 Project Overview
This project was developed as part of the CodeAlpha Cybersecurity Internship.

This project demonstrates the setup and monitoring capabilities of Snort IDS for detecting and analyzing network traffic in real time.

The objective of this project is to configure a basic Intrusion Detection System (IDS) using Snort to monitor live network traffic, inspect packets, and analyze suspicious activity.

---

## 🚀 Features
- Snort IDS installation and configuration
- Live packet monitoring
- ICMP traffic analysis
- Real-time packet inspection
- Network traffic monitoring
- Packet capture analysis
- Log generation
- Linux-based IDS setup

---

## 🛠️ Tools & Technologies Used
- Kali Linux
- Snort IDS
- Linux Terminal
- Networking Concepts
- Git & GitHub

---

## 📂 Project Structure

```text
CodeAlpha_NetworkIDS/
│
├── configuration/
│   └── snort_commands.txt
│
├── logs/
│   └── alert_logs.txt
│
├── screenshots/
│   ├── day1_snort_version.png
│   ├── day1_snort_test.png
│   ├── day2_packet_monitoring.png
│   ├── day2_ping_test.png
│   
│
├── learning_notes.md
├── README.md
```

---

## 🔍 Monitoring Activities Performed
- Live packet monitoring
- ICMP ping traffic analysis
- Real-time traffic inspection
- Packet capture monitoring
- Network interface monitoring

---

## 📸 Screenshots

### Snort Installation Verification
![Snort Version](screenshots/day1_snort_version.png)

### Snort Configuration Test
![Snort Test](screenshots/day1_snort_test.png)

### Live Packet Monitoring
![Packet Monitoring](screenshots/day2_packet_monitoring.png)

### Ping Traffic Analysis
![Ping Test](screenshots/day2_ping_test.png)

---

## 📝 Commands Used

### Install Snort
```bash
sudo apt update
sudo apt install snort -y
```

### Check Snort Version
```bash
snort -V
```

### Test Snort Configuration
```bash
sudo snort -T -c /etc/snort/snort.lua
```

### Start Packet Monitoring
```bash
sudo snort -i eth0 -v
```

### Generate ICMP Traffic
```bash
ping 8.8.8.8
```

---

## 📚 Key Concepts Learned
- Intrusion Detection Systems (IDS)
- Network packet monitoring
- Real-time traffic analysis
- ICMP traffic monitoring
- Snort configuration and usage
- Linux-based cybersecurity tools

---

## 🎯 Objective
To understand how Intrusion Detection Systems monitor and analyze network traffic to identify suspicious activities and improve cybersecurity monitoring.

---

## ✅ Project Outcome
Successfully installed and configured Snort IDS on Kali Linux and monitored live network traffic using packet inspection techniques.

---

## 👨‍💻 Author
Nensi Shingala