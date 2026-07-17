# 🛡️ Nmap Live Host Discovery

> *A network reconnaissance lab completed as part of the TryHackMe Penetration Tester learning path, focusing on identifying live hosts using Nmap's host discovery techniques.*

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
| 🌐 Category | Network Discovery & Enumeration |
| 📅 Completed | 17th July 2026 |
| 📈 Status | Completed |

---

# 🎯 Why I Completed This Lab

As part of my penetration testing learning journey, I completed this lab to understand how Nmap performs host discovery before port scanning. Identifying active systems is one of the first steps in any security assessment, allowing reconnaissance efforts to remain focused on reachable targets while reducing unnecessary scanning.

---

# 🚀 Objective

Develop practical experience with Nmap host discovery by:

- Understanding multiple host discovery techniques.
- Learning when different probe types are appropriate.
- Identifying live hosts without performing port scans.
- Comparing ARP, ICMP, TCP, and UDP discovery methods.
- Building a foundation for later enumeration and port scanning.

---

# ⚡ Host Discovery Workflow

```text
Target Network
        │
        ▼
Host Discovery
        │
        ▼
Identify Live Hosts
        │
        ▼
Validate Reachability
        │
        ▼
Target Selection
        │
        ▼
Port Scanning & Enumeration
```

---

# 🧠 Skills Practiced

- ✅ Host Discovery
- ✅ Nmap Fundamentals
- ✅ ARP Discovery
- ✅ ICMP Discovery
- ✅ TCP SYN & ACK Discovery
- ✅ UDP Discovery
- ✅ Network Enumeration
- ✅ Scan Planning

---

# 🛠️ Technologies & Tools

| Tool | Purpose |
|------|---------|
| Nmap | Host discovery and network enumeration |
| ARP | Local network host identification |
| ICMP | Network reachability testing |
| TCP | Active host verification |
| UDP | Service-based host discovery |

---

# 🔍 Methodology

## 🌐 Phase 1 – ARP Host Discovery

The lab introduced ARP-based discovery for identifying live hosts on a local network. Because ARP operates at Layer 2, it provides a reliable method for discovering systems within the same broadcast domain.

---

## 📡 Phase 2 – ICMP Discovery

I explored several ICMP-based discovery techniques, including Echo, Timestamp, and Address Mask requests. These probes demonstrate how different ICMP message types can determine host availability depending on network filtering rules.

---

## 🔀 Phase 3 – TCP Discovery

The assessment covered TCP SYN and TCP ACK ping scans, which determine whether a host is online by sending TCP probes to selected ports. These techniques are useful when ICMP traffic is restricted or filtered.

---

## 📨 Phase 4 – UDP Discovery

UDP-based host discovery was introduced as another method for validating host availability, particularly when targeting services that commonly operate over UDP.

---

## 📝 Phase 5 – Scan Optimization

The final stage focused on using Nmap options such as host-only discovery and DNS lookup controls to perform efficient reconnaissance before initiating more detailed enumeration and port scanning.

---

# 🚨 Key Findings

| Severity | Finding | Impact |
|-----------|----------|--------|
| 🟢 Informational | Multiple discovery methods improve host identification | Increases reconnaissance reliability across different environments |
| 🟢 Informational | Different protocols bypass different filtering rules | Enables more flexible host discovery |
| 🟢 Informational | Host discovery reduces unnecessary scanning | Improves efficiency during assessments |

---

# 🛡️ Best Practices Reinforced

- Perform host discovery before port scanning.
- Select discovery techniques based on network conditions.
- Combine multiple probe types when appropriate.
- Minimize unnecessary network traffic during reconnaissance.
- Document identified hosts before beginning service enumeration.

---

# 💡 What I Learned

This lab reinforced that effective enumeration begins with accurately identifying which systems are actually online. Rather than relying on a single discovery technique, Nmap provides multiple methods using ARP, ICMP, TCP, and UDP probes, allowing host discovery to remain effective even when certain protocols are filtered.

One of my biggest takeaways was understanding that successful reconnaissance depends on choosing the appropriate discovery method for the environment being assessed. Building an accurate list of live hosts creates a stronger foundation for later port scanning, service enumeration, and vulnerability assessment.

---

# 📚 References

- TryHackMe – Nmap Live Host Discovery
- Nmap Documentation
- RFC 792 – Internet Control Message Protocol (ICMP)
- RFC 826 – Address Resolution Protocol (ARP)

---

# ⚖️ Disclaimer

This documentation summarizes work completed within an authorized TryHackMe training environment for educational purposes only. The report focuses on host discovery techniques, Nmap methodology, and professional documentation. Challenge answers and platform-specific solutions have intentionally been omitted.
