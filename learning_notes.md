# Day 1 - Snort IDS Setup

## What is IDS
An Intrusion Detection System (IDS) monitors network traffic or system activity to detect suspicious behavior, attacks, or unauthorized access attempts.

## Types of IDS

### Network IDS (NIDS)
Monitors network traffic across a network to identify malicious activity.

### Host IDS (HIDS)
Monitors activity on a specific device or host system.

## What is Snort
Snort is an open-source Network Intrusion Detection System used for:
- Real-time traffic analysis
- Packet monitoring
- Intrusion detection
- Network security monitoring

## Work Completed
- Installed Snort on Kali Linux
- Verified Snort installation
- Tested Snort configuration

## Commands Used

### Update System
```bash
sudo apt update
```

### Install Snort
```bash
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

## Key Learning
Snort uses packet inspection and rule-based detection to monitor network traffic and identify suspicious activities.

---

# Day 2 - Network Traffic Monitoring

## Objective
Monitor live network traffic using Snort and analyze packet activity.

## Work Completed
- Started Snort packet monitoring
- Selected correct network interface
- Generated ICMP ping traffic
- Observed live packet monitoring

## Network Interface Used
```text
eth0
```

## Commands Used

### Check Network Interface
```bash
ip a
```

### Start Snort Monitoring
```bash
sudo snort -i eth0 -v
```

### Generate Network Traffic
```bash
ping 8.8.8.8
```

## Observations
- Snort successfully monitored live packets.
- ICMP traffic was visible during ping activity.
- Packet processing was active on the selected interface.

## Concepts Learned

### Packet Monitoring
Snort can inspect packets flowing through the network interface in real time.

### ICMP Traffic
Ping commands generate ICMP packets which can be monitored using IDS tools.

### Network Interface
The network interface acts as the communication point used by Snort to capture traffic.

## Key Learning
Intrusion Detection Systems can continuously monitor network traffic and help identify suspicious or malicious activity.

---

# Overall Project Learning

## Skills Gained
- Snort installation and configuration
- Network packet monitoring
- Basic intrusion detection concepts
- Linux terminal usage
- Network interface analysis
- GitHub project documentation

## Cybersecurity Concepts Learned
- Intrusion Detection Systems
- Network monitoring
- Packet analysis
- ICMP traffic monitoring
- Real-time traffic inspection

## Final Understanding
Network Intrusion Detection Systems help improve cybersecurity by monitoring network traffic, analyzing packets, and identifying suspicious behavior in real time.