# 🛡️ Nmap Basic Port Scans

> *A network enumeration lab completed as part of the TryHackMe Penetration Tester learning path, introducing the fundamental port scanning techniques available in Nmap for identifying exposed TCP and UDP services.*

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
| 🌐 Category | Network Enumeration & Port Scanning |
| 📅 Completed | 20th July 2026 |
| 📈 Status | Completed |

---

# 🎯 Why I Completed This Lab

As part of my penetration testing learning journey, I completed this lab to understand how Nmap discovers open services on target systems. Port scanning is one of the core phases of reconnaissance, providing insight into a system's attack surface before moving into service enumeration and vulnerability assessment.

---

# 🚀 Objective

Develop practical experience with Nmap port scanning by:

- Understanding common TCP and UDP scan types.
- Comparing different scanning techniques.
- Learning how scan options affect speed and coverage.
- Identifying exposed network services.
- Building a foundation for advanced enumeration.

---

# ⚡ Port Scanning Workflow

```text
Target Host
      │
      ▼
Host Discovery
      │
      ▼
Port Scan
      │
      ▼
Identify Open Services
      │
      ▼
Service Enumeration
      │
      ▼
Vulnerability Assessment
```

---

# 🧠 Skills Practiced

- ✅ TCP Connect Scanning
- ✅ TCP SYN Scanning
- ✅ UDP Scanning
- ✅ Network Enumeration
- ✅ Service Discovery
- ✅ Scan Optimization
- ✅ Reconnaissance Planning
- ✅ Nmap Fundamentals

---

# 🛠️ Technologies & Tools

| Tool | Purpose |
|------|---------|
| Nmap | Network discovery and port scanning |
| TCP Connect Scan | Full TCP three-way handshake scanning |
| TCP SYN Scan | Half-open port scanning |
| UDP Scan | Discovery of UDP services |

---

# 🔍 Methodology

## 🌐 Phase 1 – TCP Connect Scan

The lab introduced the TCP Connect Scan, which establishes a complete TCP three-way handshake before closing the connection. This method is widely supported and can be performed without elevated privileges, making it useful when administrative access is unavailable.

---

## ⚡ Phase 2 – TCP SYN Scan

Next, I explored the TCP SYN Scan, often referred to as a half-open scan. Instead of completing the full handshake, the scan determines port status based on the target's response, making it faster and less intrusive than a full TCP connection.

---

## 📨 Phase 3 – UDP Scan

The assessment also covered UDP scanning, demonstrating how Nmap identifies services that rely on UDP rather than TCP. Since many critical infrastructure services operate over UDP, incorporating UDP scans helps produce a more complete picture of a target's exposed services.

---

## ⚙️ Phase 4 – Scan Configuration

The final section focused on configuring Nmap scans by selecting specific port ranges, adjusting scan timing, controlling packet rates, and increasing probe parallelism to balance scan speed with reliability.

---

# 🚨 Key Findings

| Severity | Finding | Impact |
|-----------|----------|--------|
| 🟢 Informational | Different scan types provide different visibility into network services | Improves reconnaissance flexibility |
| 🟢 Informational | Scan configuration affects speed, accuracy, and network footprint | Enables efficient enumeration |
| 🟢 Informational | UDP services should not be overlooked during assessments | Expands attack surface visibility |

---

# 🛡️ Best Practices Reinforced

- Perform host discovery before initiating port scans.
- Use the appropriate scan type based on privileges and assessment objectives.
- Include UDP scanning where applicable to improve service coverage.
- Adjust scan timing responsibly to minimize unnecessary network impact.
- Document discovered services before beginning deeper enumeration.

---

# 💡 What I Learned

This lab reinforced that effective port scanning involves more than simply running Nmap with default options. Understanding the differences between TCP Connect, TCP SYN, and UDP scans helps security professionals choose the most appropriate technique for a given environment while balancing efficiency, accuracy, and network impact.

One of my biggest takeaways was that scan configuration is just as important as the scan itself. Selecting the right port range, timing options, and scanning methodology leads to more reliable reconnaissance and provides a stronger foundation for later stages of a penetration test.

---

# 📚 References

- TryHackMe – Nmap Basic Port Scans
- Nmap Documentation
- RFC 793 – Transmission Control Protocol (TCP)
- RFC 768 – User Datagram Protocol (UDP)

---

# ⚖️ Disclaimer

This documentation summarizes work completed within an authorized TryHackMe training environment for educational purposes only. The report focuses on network enumeration methodology, Nmap scanning techniques, and professional documentation. Challenge answers and platform-specific solutions have intentionally been omitted.
