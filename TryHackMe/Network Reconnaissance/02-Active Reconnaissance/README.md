# 🛡️ Active Reconnaissance

> *A reconnaissance-focused lab completed as part of the TryHackMe Penetration Tester learning path, introducing the fundamental tools and techniques used during active information gathering.*

![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![Platform](https://img.shields.io/badge/Platform-TryHackMe-red)
![Category](https://img.shields.io/badge/Category-Reconnaissance-blue)
![Learning Path](https://img.shields.io/badge/Path-Penetration%20Tester-orange)

---

## 📋 Lab Information

| Property | Details |
|-----------|---------|
| 🎯 Platform | TryHackMe |
| 🛣️ Learning Path | Penetration Tester |
| 🔎 Category | Active Reconnaissance |
| 📅 Completed | 15th July 2026 |
| 📈 Status | Completed |

---

# 🎯 Why I Completed This Lab

As part of my penetration testing learning journey, I completed this lab to strengthen my understanding of active reconnaissance and the manual techniques used to interact directly with target systems.

Rather than relying entirely on automated scanners, this room focused on validating hosts, identifying services, inspecting web applications, and manually communicating with network services to better understand a target's exposed attack surface.

---

# 🚀 Objective

Develop practical experience with active reconnaissance by:

- Verifying host availability.
- Inspecting network paths.
- Performing manual banner grabbing.
- Understanding HTTP communication over raw TCP.
- Building a structured foundation for enumeration and service discovery.

---

# ⚡ Active Reconnaissance Workflow

```text
Target Validation
        │
        ▼
Host Discovery
        │
        ▼
Network Path Analysis
        │
        ▼
Service Identification
        │
        ▼
Manual Banner Grabbing
        │
        ▼
Attack Surface Assessment
```

---

# 🧠 Skills Practiced

- ✅ Active Reconnaissance
- ✅ Host Discovery
- ✅ Network Path Analysis
- ✅ Manual Banner Grabbing
- ✅ HTTP Request Construction
- ✅ Service Identification
- ✅ Web Application Inspection
- ✅ Technical Documentation

---

# 🛠️ Technologies & Tools

| Tool | Purpose |
|------|---------|
| Browser Developer Tools | Inspect web technologies, certificates, and client-side resources |
| ping | Verify host availability and analyze latency |
| traceroute / tracert | Map the network path to the target |
| telnet | Manual TCP communication with network services |
| Netcat (nc) | Banner grabbing and service interaction |
| curl | Retrieve HTTP response headers and identify web servers |

---

# 🔍 Methodology

## 🌐 Phase 1 – Target Validation

The assessment began by confirming that the target was reachable using **ping**. This established basic network connectivity and demonstrated how response characteristics, such as latency and TTL values, can provide useful reconnaissance information.

---

## 🛣️ Phase 2 – Network Path Analysis

Using **traceroute**, I examined the route packets followed to reach the target system. Understanding intermediate network hops provided additional context about the target's infrastructure before interacting directly with exposed services.

---

## 🔎 Phase 3 – Service Identification

I manually connected to exposed services using **Telnet** and **Netcat**, establishing raw TCP connections to validate service availability and identify listening applications.

This exercise reinforced how manual interaction with services can complement automated scanners during penetration testing engagements.

---

## 🌐 Phase 4 – HTTP Banner Grabbing

After establishing TCP connectivity, I manually constructed HTTP requests to retrieve response headers from the target web server.

This demonstrated the importance of correctly formatting HTTP/1.1 requests, including required headers such as **Host**, to successfully communicate with modern web servers and accurately identify running technologies.

---

## 📝 Phase 5 – Assessment Planning

The final stage emphasized how lightweight reconnaissance tools work together to build an understanding of a target before using more advanced enumeration utilities such as Nmap.

These techniques provide quick validation while improving familiarity with the underlying protocols that automated tools rely upon.

---

# 🚨 Key Findings

| Severity | Finding | Impact |
|-----------|----------|--------|
| 🟢 Informational | Successful manual TCP connectivity | Confirmed accessible network services |
| 🟢 Informational | HTTP banner retrieval | Identified service characteristics through manual requests |
| 🟢 Informational | Multi-tool reconnaissance workflow | Improved validation through complementary techniques |

---

# 🛡️ Best Practices Reinforced

- Validate host availability before performing deeper enumeration.
- Use multiple reconnaissance techniques to confirm findings.
- Construct properly formatted HTTP requests when interacting with web services manually.
- Prefer **Netcat** or **curl** over **Telnet** for modern HTTP banner grabbing where appropriate.
- Document reconnaissance findings before moving into vulnerability assessment.

---

# 💡 What I Learned

This lab reinforced that effective reconnaissance is built upon understanding the underlying network protocols rather than relying solely on automated tools. By manually communicating with services using Telnet and Netcat, I gained a deeper appreciation for how HTTP requests, service banners, and raw TCP communication contribute to the early stages of a penetration test.

One of my biggest takeaways was that correctly formatted HTTP requests are essential for accurate service identification and banner grabbing. Understanding these fundamentals provides stronger context when later using automated tools such as Nmap or Burp Suite.

---

# 📚 References

- TryHackMe – Active Reconnaissance
- Netcat Documentation
- curl Documentation
- traceroute Manual
- RFC 9112 – HTTP/1.1

---

# ⚖️ Disclaimer

This documentation summarizes work completed within an authorized TryHackMe training environment for educational purposes only. The report focuses on reconnaissance methodology, commonly used security tools, and professional documentation. Challenge answers and platform-specific solutions have intentionally been omitted.
