# 🦈 Wireshark Packet Analysis Lab

> A hands-on networking lab focused on packet capture, DNS analysis, and ICMP troubleshooting using Wireshark in a Windows 11 Virtual Machine.

---

## 📖 Project Overview

In this lab, I used Wireshark to capture and analyze live network traffic generated from a Windows 11 virtual machine. The objective was to gain practical experience with packet analysis, identify DNS queries and responses, examine ICMP traffic, and better understand how devices communicate across a network.

---

## 🎯 Objectives

✅ Capture live network traffic

✅ Analyze DNS queries and responses

✅ Analyze ICMP (Ping) traffic

✅ Identify source and destination IP addresses

✅ Examine packet headers and protocol details

✅ Develop foundational packet analysis skills

---

## 🛠️ Technologies & Tools

| Tool | Purpose |
|--------|--------|
| Wireshark | Packet Capture & Analysis |
| Windows 11 VM | Lab Environment |
| Command Prompt | Network Testing |
| DNS | Domain Name Resolution |
| ICMP | Connectivity Testing |

---

# 🌐 DNS Traffic Analysis

DNS (Domain Name System) translates human-readable domain names into IP addresses that computers use to communicate.

### DNS Traffic Capture

![DNS Traffic](Screenshots/dns-traffic.png)

**Key Observation:**
- Captured multiple DNS requests and responses.
- Observed communication between the Windows VM and DNS server.
- Identified domain resolution activity for various web services.

---

### DNS Packet Details

![DNS Packet Details](Screenshots/dns-packet-details.png)

**Analysis:**
- Examined Ethernet and IPv4 packet headers.
- Identified source and destination MAC addresses.
- Verified source and destination IP addresses.
- Observed packet encapsulation across network layers.

---

### DNS Query Analysis

![DNS Query Details](Screenshots/dns-query-details.png)

**Analysis:**
- Investigated a DNS query for `open.spotify.com`.
- Examined DNS query structure.
- Identified query type and requested resource.
- Reviewed packet contents using Wireshark's packet detail pane.

---

# 📡 ICMP (Ping) Analysis

ICMP is commonly used to test network connectivity and troubleshoot communication issues between devices.

### ICMP Packet Analysis

![ICMP Analysis](Screenshots/icmp-analysis.png)

**Analysis:**
- Captured ICMP Echo Requests and Echo Replies.
- Verified successful communication between the VM and an external host.
- Confirmed internet connectivity.
- Observed packet sequence numbers and response behavior.

---

# 🔍 Key Findings

### DNS Analysis
- Successfully captured DNS requests and responses.
- Observed how domain names are resolved into IP addresses.
- Examined DNS packet structure and query information.

### ICMP Analysis
- Successfully captured ICMP Echo Requests and Replies.
- Verified network connectivity.
- Observed packet exchanges between source and destination hosts.

### Packet Inspection
- Analyzed Ethernet, IPv4, DNS, and ICMP protocols.
- Examined packet headers and network-layer information.
- Used Wireshark filtering to isolate specific traffic types.

---

# 🧠 Skills Demonstrated

- Packet Capture
- Packet Analysis
- Network Troubleshooting
- DNS Investigation
- ICMP Analysis
- Protocol Identification
- Wireshark Navigation
- Traffic Filtering
- Network Fundamentals

---

# 📚 What I Learned

This lab provided practical experience using Wireshark to inspect real network traffic. By analyzing DNS and ICMP packets, I gained a better understanding of how devices communicate across networks, how domain names are resolved, and how packet analysis can be used to troubleshoot connectivity issues.

---

## ⭐ Repository Purpose

This project is part of my IT and Cybersecurity Home Lab portfolio, where I document hands-on technical projects to develop practical networking, troubleshooting, and security skills.
