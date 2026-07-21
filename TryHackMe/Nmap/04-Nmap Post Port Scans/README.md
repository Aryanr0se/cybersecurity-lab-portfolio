# 🛡️ Nmap Post Port Scans

> *A network enumeration lab completed as part of the TryHackMe Penetration Tester learning path, focusing on service detection, operating system fingerprinting, NSE scripting, traceroute analysis, and scan result management using Nmap.*

![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![Platform](https://img.shields.io/badge/Platform-TryHackMe-red)
![Category](https://img.shields.io/badge/Category-Nmap-blue)
![Learning Path](https://img.shields.io/badge/Path-Penetration%20Tester-orange)

---

## 📋 Lab Information

| Property | Details |
|-----------|---------|
| 🎯 Platform | TryHackMe |
| 🛣️ Learning Path | Penetration Tester |
| 🌐 Category | Service Enumeration & Post Port Scanning |
| 📅 Completed | 21st July 2026 |
| 📈 Status | Completed |

---

# 🎯 Why I Completed This Lab

As part of my penetration testing learning journey, I completed this lab to explore what comes after identifying open ports. Rather than stopping at port discovery, the focus shifted to determining running services, identifying operating systems, leveraging the Nmap Scripting Engine (NSE), and organizing scan results for future analysis.

---

# 🚀 Objective

Develop practical experience with Nmap post-port scanning by:

- Identifying services and software versions.
- Detecting operating systems.
- Running NSE scripts for automated enumeration.
- Understanding traceroute integration.
- Saving scan results for later analysis.

---

# ⚡ Enumeration Workflow

```text
Host Discovery
      │
      ▼
Port Scan
      │
      ▼
Service Detection
      │
      ▼
Operating System Detection
      │
      ▼
NSE Script Enumeration
      │
      ▼
Reporting & Documentation
```

---

# 🧠 Skills Practiced

- ✅ Service Version Detection
- ✅ Operating System Fingerprinting
- ✅ Nmap Scripting Engine (NSE)
- ✅ Traceroute Analysis
- ✅ SSH Enumeration
- ✅ Scan Result Management
- ✅ Service Enumeration
- ✅ Network Reconnaissance

---

# 🛠️ Technologies & Tools

| Tool | Purpose |
|------|---------|
| Nmap | Service detection and enumeration |
| Nmap Scripting Engine (NSE) | Automated protocol-specific enumeration |
| Traceroute | Network path analysis |
| SSH Enumeration Scripts | Identify supported SSH algorithms |
| Nmap Output Formats | Structured scan result storage |

---

# 🔍 Methodology

## 🔎 Phase 1 – Service Detection

The assessment began by identifying services running on discovered ports using Nmap's version detection capabilities. Adjusting probe intensity demonstrated how scan depth can balance speed with fingerprinting accuracy.

---

## 🖥️ Phase 2 – Operating System Fingerprinting

Next, I explored operating system detection by analyzing responses generated during the scan. Understanding the host operating system provides valuable context when planning further enumeration or vulnerability assessment.

---

## ⚙️ Phase 3 – Nmap Scripting Engine

The lab introduced the Nmap Scripting Engine (NSE), beginning with the default script set before moving to targeted scripts for SSH enumeration.

Using NSE expanded reconnaissance beyond basic port information by collecting protocol-specific details, including supported SSH algorithms and service capabilities.

---

## 🌐 Phase 4 – Network Path Analysis

Traceroute functionality was incorporated into the scan to identify the route between the scanning host and the target. Combining routing information with service enumeration provides additional visibility into the target's network environment.

---

## 📝 Phase 5 – Scan Documentation

The final stage focused on exporting scan results in multiple formats, allowing findings to be archived, parsed, and referenced during future assessments without repeating scans.

---

# 🚨 Key Findings

| Severity | Finding | Impact |
|-----------|----------|--------|
| 🟢 Informational | Service version detection identified exposed software | Supports targeted vulnerability assessment |
| 🟢 Informational | NSE scripts provided protocol-specific information | Improves depth of enumeration |
| 🟢 Informational | Structured scan outputs improve reporting and reproducibility | Enables efficient documentation and analysis |

---

# 🛡️ Best Practices Reinforced

- Perform service detection after identifying open ports.
- Use NSE scripts to enrich reconnaissance with protocol-specific information.
- Balance scan intensity based on assessment objectives.
- Save scan results for future reference and reporting.
- Verify scan options to avoid combining incompatible flags.

---

# 💡 What I Learned

This lab reinforced that identifying open ports is only the beginning of network enumeration. Understanding the services behind those ports, their versions, supported protocols, and operating system characteristics provides far more meaningful information for a security assessment.

One of my biggest takeaways was learning how the Nmap Scripting Engine extends reconnaissance by automating service-specific enumeration while also recognizing the importance of understanding scan option interactions to avoid unintended behavior. Saving scan results in multiple formats also highlighted the importance of maintaining reproducible assessment artifacts for documentation and future analysis.

---

# 📚 References

- TryHackMe – Nmap Post Port Scans
- Nmap Documentation
- Nmap Scripting Engine (NSE) Documentation
- Nmap Network Scanning Guide

---

# ⚖️ Disclaimer

This documentation summarizes work completed within an authorized TryHackMe training environment for educational purposes only. The report focuses on service enumeration, Nmap methodology, and professional documentation. Challenge answers and platform-specific solutions have intentionally been omitted.
