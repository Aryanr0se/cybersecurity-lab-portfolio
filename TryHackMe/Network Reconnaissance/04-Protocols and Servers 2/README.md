# 🛡️ Protocols and Servers 2

> *A networking security lab completed as part of the TryHackMe Penetration Tester learning path, exploring common attacks against network protocols and the defensive controls used to mitigate them.*

![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![Platform](https://img.shields.io/badge/Platform-TryHackMe-red)
![Category](https://img.shields.io/badge/Category-Network%20Security-blue)
![Learning Path](https://img.shields.io/badge/Path-Penetration%20Tester-orange)

---

## 📋 Lab Information

| Property | Details |
|-----------|---------|
| 🎯 Platform | TryHackMe |
| 🛣️ Learning Path | Penetration Tester |
| 🌐 Category | Network Security |
| 📅 Completed | 17th July 2026 |
| 📈 Status | Completed |

---

# 🎯 Why I Completed This Lab

As part of my penetration testing learning journey, I completed this lab to understand how common network protocols are attacked and, more importantly, how those attacks can be prevented. The room focused on viewing protocols from both an offensive and defensive perspective, reinforcing why secure protocol selection and strong authentication are fundamental to modern cybersecurity.

---

# 🚀 Objective

Develop a practical understanding of protocol-level attacks by:

- Understanding common attacks against network protocols.
- Identifying weaknesses in cleartext communications.
- Exploring password attacks against network services.
- Learning defensive controls that reduce attack surface.
- Understanding secure protocol alternatives and authentication best practices.

---

# ⚡ Attack Lifecycle

```text
Reconnaissance
        │
        ▼
Traffic Capture
        │
        ▼
Credential Collection
        │
        ▼
Authentication Attack
        │
        ▼
System Access
        │
        ▼
Mitigation & Hardening
```

---

# 🧠 Skills Practiced

- ✅ Network Traffic Analysis
- ✅ Sniffing Attack Concepts
- ✅ Man-in-the-Middle (MITM)
- ✅ Password Attack Methodology
- ✅ Protocol Hardening
- ✅ TLS Fundamentals
- ✅ Authentication Security
- ✅ Defensive Security Controls

---

# 🛠️ Technologies & Tools

| Tool / Technology | Purpose |
|-------------------|---------|
| Hydra | Password auditing and brute-force testing |
| Wireshark | Network packet capture and analysis |
| tcpdump | Command-line packet capture |
| Bettercap | MITM and network attacks |
| mitmproxy | HTTPS interception and inspection |
| testssl.sh | TLS configuration assessment |
| Nmap | Service discovery and version detection |
| Hashcat / John the Ripper | Offline password cracking |

---

# 🔍 Methodology

## 🌐 Phase 1 – Sniffing Attacks

The lab introduced packet sniffing as one of the most fundamental attacks against cleartext protocols.

I explored how attackers monitoring network traffic can capture usernames, passwords, emails, and other sensitive information whenever encryption is not used.

This reinforced why modern services should always encrypt communications using TLS.

---

## 🔀 Phase 2 – Man-in-the-Middle (MITM)

Next, I examined how attackers position themselves between two communicating systems to intercept, inspect, or manipulate network traffic.

The room explained how improper certificate validation, weak encryption, and insecure network configurations increase the effectiveness of MITM attacks.

---

## 🔑 Phase 3 – Password Attacks

The final attack category focused on password-based authentication.

The lab introduced **Hydra** as a password auditing tool while discussing:

- Brute-force attacks
- Dictionary attacks
- Password spraying
- Authentication rate limiting
- Multi-factor authentication

This demonstrated why strong passwords alone are insufficient without additional security controls.

---

## 🛡️ Phase 4 – Defensive Security

The room concluded by exploring practical security controls that reduce protocol-related risk.

Topics included:

- TLS 1.2 / TLS 1.3 adoption
- HTTPS and HSTS
- SSH instead of Telnet
- SFTP instead of FTP
- Multi-factor authentication
- Certificate validation
- Account lockout policies
- Network segmentation

---

## 📝 Phase 5 – Security Assessment

The final stage emphasized evaluating both attack opportunities and defensive controls during security assessments.

Understanding protocol behavior enables security professionals to identify weak configurations, demonstrate their impact, and recommend effective mitigations.

---

# 🚨 Key Findings

| Severity | Finding | Impact |
|-----------|----------|--------|
| 🔴 Critical | Cleartext protocols expose sensitive information | Credentials and application data may be intercepted |
| 🟠 High | Weak password authentication | Increases susceptibility to brute-force and password spraying attacks |
| 🟡 Medium | Inadequate protocol hardening | Expands attack surface for network-based attacks |

---

# 🛡️ Best Practices Reinforced

- Replace legacy cleartext protocols with encrypted alternatives.
- Enforce TLS 1.2 or TLS 1.3 across exposed services.
- Enable HSTS for web applications.
- Implement multi-factor authentication wherever possible.
- Enforce strong password policies and account lockout mechanisms.
- Prefer SSH key-based authentication over passwords.
- Monitor authentication events for suspicious activity.
- Validate certificates to reduce MITM risk.

---

# 💡 What I Learned

This lab reinforced that many successful attacks target weaknesses in communication protocols rather than software vulnerabilities. Understanding how sniffing, man-in-the-middle attacks, and password attacks operate provides valuable insight into why encryption, authentication, and network segmentation are essential security controls.

One of my biggest takeaways was recognizing that security is most effective when both offensive techniques and defensive mitigations are understood together. Identifying insecure protocols is only the first step; recommending practical remediation strategies is equally important during a professional security assessment.

---

# 📚 References

- TryHackMe – Protocols and Servers 2
- Hydra Documentation
- Wireshark Documentation
- OWASP Transport Layer Security Cheat Sheet
- NIST SP 800-52 Rev. 2
- RFC 8446 – TLS 1.3

---

# ⚖️ Disclaimer

This documentation summarizes work completed within an authorized TryHackMe training environment for educational purposes only. The report focuses on protocol security, attack methodology, defensive controls, and professional documentation. Challenge answers and platform-specific solutions have intentionally been omitted.
