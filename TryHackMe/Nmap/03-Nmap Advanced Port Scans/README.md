# 🛡️ Nmap Advanced Port Scans

> *An advanced network enumeration lab completed as part of the TryHackMe Penetration Tester learning path, exploring stealth scanning techniques, firewall analysis, and advanced TCP flag manipulation using Nmap.*

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
| 🌐 Category | Advanced Network Enumeration & Stealth Scanning |
| 📅 Completed | 20th July 2026 |
| 📈 Status | Completed |

---

# 🎯 Why I Completed This Lab

As part of my penetration testing learning journey, I completed this lab to explore advanced Nmap scanning techniques that go beyond traditional port discovery. The room focused on using custom TCP flags and specialized scan types to gather information about target systems while understanding how firewalls and filtering mechanisms influence scan results.

---

# 🚀 Objective

Develop practical experience with advanced Nmap scanning by:

- Understanding stealth scanning techniques.
- Learning how TCP flag manipulation affects scan behavior.
- Evaluating firewall filtering and packet handling.
- Exploring scan obfuscation methods.
- Building a stronger foundation for advanced network enumeration.

---

# ⚡ Advanced Scanning Workflow

```text
Target Host
      │
      ▼
Select Scan Technique
      │
      ▼
Transmit Custom TCP Flags
      │
      ▼
Analyze Responses
      │
      ▼
Infer Port & Firewall State
      │
      ▼
Plan Further Enumeration
```

---

# 🧠 Skills Practiced

- ✅ TCP FIN Scan
- ✅ TCP NULL Scan
- ✅ TCP Xmas Scan
- ✅ TCP Maimon Scan
- ✅ TCP ACK Scan
- ✅ TCP Window Scan
- ✅ Firewall Analysis
- ✅ Stealth Enumeration

---

# 🛠️ Technologies & Tools

| Tool | Purpose |
|------|---------|
| Nmap | Advanced network discovery and enumeration |
| TCP Flag Scans | Alternative methods for probing target ports |
| ACK Scan | Firewall rule analysis |
| Decoy & Idle Scans | Scan obfuscation techniques |
| Packet Fragmentation | Reduce scan detectability |

---

# 🔍 Methodology

## 🔎 Phase 1 – TCP Flag Scanning

The lab introduced multiple TCP flag-based scans, including **NULL**, **FIN**, **Xmas**, and **Maimon** scans. Rather than relying on traditional connection establishment, these techniques manipulate TCP flags to observe how target systems respond, allowing Nmap to infer port states under different network conditions.

---

## 🛡️ Phase 2 – Firewall Analysis

I explored **TCP ACK** and **TCP Window** scans to evaluate firewall behavior rather than service availability.

These scan types helped distinguish filtered and unfiltered traffic, demonstrating how firewall rules influence reconnaissance results and assist in mapping network security controls.

---

## 🎭 Phase 3 – Scan Evasion

The assessment introduced techniques designed to reduce scan visibility, including:

- Decoy scans
- Idle (Zombie) scans
- Source IP spoofing
- MAC address spoofing
- Packet fragmentation
- Custom TCP flag combinations

Understanding these methods highlighted how attackers may attempt to bypass simple filtering or disguise scan origins during reconnaissance.

---

## ⚙️ Phase 4 – Scan Validation

The lab emphasized validating scan results using Nmap options such as verbose output and the `--reason` flag, providing greater transparency into how Nmap reached its conclusions based on observed packet responses.

---

# 🚨 Key Findings

| Severity | Finding | Impact |
|-----------|----------|--------|
| 🟢 Informational | ACK scans identify firewall behavior | Improves understanding of network filtering |
| 🟢 Informational | TCP flag scans provide alternative enumeration methods | Useful when traditional scans are restricted |
| 🟢 Informational | Scan validation improves result accuracy | Supports reliable assessment documentation |

---

# 🛡️ Best Practices Reinforced

- Select scan techniques appropriate for the assessment objective.
- Validate scan results using packet-level evidence where possible.
- Use the `--reason` option to understand Nmap's conclusions.
- Recognize the difference between firewall filtering and service availability.
- Document reconnaissance methodology alongside scan results.

---

# 💡 What I Learned

This lab reinforced that advanced port scanning is about understanding network behavior rather than simply identifying open ports. Different TCP flag combinations produce different responses depending on the operating system, firewall configuration, and target service, allowing security professionals to gather additional information even in filtered environments.

One of my biggest takeaways was learning to distinguish between identifying exposed services and understanding how network security controls influence scan results. Recognizing this distinction leads to more accurate reconnaissance and better-informed penetration testing decisions.

---

# 📚 References

- TryHackMe – Nmap Advanced Port Scans
- Nmap Documentation
- RFC 793 – Transmission Control Protocol (TCP)
- Nmap Network Scanning Guide

---

# ⚖️ Disclaimer

This documentation summarizes work completed within an authorized TryHackMe training environment for educational purposes only. The report focuses on advanced Nmap techniques, reconnaissance methodology, and professional documentation. Challenge answers and platform-specific solutions have intentionally been omitted.
