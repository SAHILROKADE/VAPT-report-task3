# VAPT-report-task3

This repository contains the **Vulnerability Assessment and Penetration Testing (VAPT)** Report conducted on the target system with IP address `192.168.137.128` as part of a cybersecurity project.

# Vulnerability Assessment Report – Localhost

## 🛠️ Tool Used
- **Nessus Essentials** (Free version)

## 🎯 Scan Target
- **IP Address Scanned:** 192.168.137.128 (Localhost)

## 🕒 Scan Summary
- **Date of Scan:** [Add your scan date here]
- **Duration:** Approximately 30–60 minutes
- **Total Vulnerabilities Found:** [Add count based on your screenshots]
  - 🔴 Critical: [e.g., 1]
  - 🟠 High: [e.g., 3]
  - 🟡 Medium: [e.g., 5]
  - 🟢 Low: [e.g., 2]
  - ⚪ Info: [Optional]

## 📋 Key Vulnerabilities Documented

### 1. ❌ **SSL Certificate Cannot Be Trusted**
- **Severity:** High
- **Description:** The SSL certificate for the scanned system is not trusted because it is self-signed or issued by an unknown authority.
- **Impact:** Could lead to man-in-the-middle (MITM) attacks as the connection is not verifiably secure.
- **Mitigation:** Use a valid SSL certificate issued by a recognized Certificate Authority (e.g., Let’s Encrypt).

---

### 2. ❌ **Python Tornado 6.5.0 - Denial of Service (DoS)**
- **Severity:** High
- **Description:** Detected outdated Tornado version with known DoS vulnerability (CVE-2023-5217).
- **Impact:** Could allow remote attackers to exhaust system resources or crash the service.
- **Mitigation:** Upgrade Tornado to the latest secure version.

---

### 3. ❌ **Node.js 18.x Vulnerabilities**
- **Severity:** Medium–High
- **Description:** Multiple vulnerabilities present in the installed Node.js version.
- **Impact:** May include command injection, buffer overflows, or arbitrary code execution.
- **Mitigation:** Update Node.js to the latest LTS release.

---

## 🖼️ Screenshots Provided
- `scan_summary.png` – Full summary of vulnerabilities.
- `ssl_cert_issue.png` – Detailed SSL error view.
- `tornado_vuln.png` – Tornado version vulnerability.
- `nodejs_vuln.png` – Node.js CVE listing.
- Add other relevant screenshots like:
  - Plugin Output
  - Scan settings
  - Top 10 Vulnerabilities

---

## 📚 Conclusion
This vulnerability scan was performed as part of a cybersecurity training program using **Nessus Essentials**. All actions were taken in a safe lab environment. The goal was to identify and understand common local vulnerabilities and how to mitigate them effectively.

> 🧠 Learning Outcome: Learned about SSL validation issues, open-source library vulnerabilities, and the importance of keeping software dependencies updated.

---

**Submitted by:**  
👤 Sahil Rokade  
📧 sahilrokade6400@gmail.com  
📱 9321741190
