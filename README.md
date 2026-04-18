# 🕵️ Wireshark Packet Analysis (DNS Traffic)

## 📌 Overview

Performed network packet analysis using Wireshark to inspect DNS queries and responses, focusing on domain resolution and communication patterns.

---

## 🛠 Tools Used

* Wireshark

---

## 📂 Dataset

* Sample PCAP file (analyzed locally)

---

## 🔍 Analysis Performed

### 1. DNS Query Inspection

* Observed DNS queries for `ntp.ubuntu.com`
* Identified both A (IPv4) and AAAA (IPv6) requests

### 2. DNS Response Analysis

* Extracted resolved IP addresses:

  * 91.189.89.199
  * 91.189.94.4

### 3. Local DNS Communication

* Analyzed traffic between:

  * 127.0.0.1
  * 127.0.1.1
* Indicates local DNS resolver activity

### 4. Domain Authority Information

* Identified authoritative server:

  * ns1.canonical.com

---

## 📸 Screenshots

### DNS Response

dns filter.png

### TCP/DNS Details

packet analysis.png

---

## 🧠 Key Learnings

* Understood DNS packet structure
* Learned how domain names are resolved to IP addresses
* Gained experience analyzing real network traffic

---

## 🚀 Conclusion

Successfully analyzed DNS traffic using Wireshark and extracted meaningful insights from raw packet data.

---
