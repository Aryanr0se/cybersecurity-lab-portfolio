# 🛡️ Protocols and Servers

> *A networking-focused lab completed as part of the TryHackMe Penetration Tester learning path, exploring common application-layer protocols, manual protocol interaction, and the security implications of transmitting data over unencrypted channels.*

![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![Platform](https://img.shields.io/badge/Platform-TryHackMe-red)
![Category](https://img.shields.io/badge/Category-Networking-blue)
![Learning Path](https://img.shields.io/badge/Path-Penetration%20Tester-orange)

---

## 📋 Lab Information

| Property | Details |
|-----------|---------|
| 🎯 Platform | TryHackMe |
| 🛣️ Learning Path | Penetration Tester |
| 🌐 Category | Networking & Application Protocols |
| 📅 Completed | 16th July 2026 |
| 📈 Status | Completed |

---

# 🎯 Why I Completed This Lab

As part of my penetration testing learning journey, I completed this lab to strengthen my understanding of common application-layer protocols and how they communicate across a network.

Rather than simply learning default ports, the room focused on interacting directly with services using Telnet to understand protocol behavior, authentication flows, and why transmitting data in cleartext presents significant security risks.

---

# 🚀 Objective

Develop a practical understanding of common network protocols by:

- Understanding how application-layer protocols operate.
- Interacting directly with network services.
- Learning manual protocol communication.
- Identifying security risks associated with cleartext protocols.
- Understanding secure protocol alternatives.

---

# ⚡ Protocol Workflow

```text
Client Connection
        │
        ▼
Protocol Handshake
        │
        ▼
Command Exchange
        │
        ▼
Authentication
        │
        ▼
Data Transfer
        │
        ▼
Session Termination
```

---

# 🧠 Skills Practiced

- ✅ HTTP Communication
- ✅ FTP Fundamentals
- ✅ SMTP Fundamentals
- ✅ POP3 & IMAP Concepts
- ✅ Telnet Service Interaction
- ✅ Banner Grabbing
- ✅ Manual Protocol Analysis
- ✅ Network Security Awareness

---

# 🛠️ Technologies & Tools

| Tool | Purpose |
|------|---------|
| Telnet | Manual interaction with TCP services |
| FTP | File transfer protocol testing |
| HTTP | Web protocol communication |
| SMTP | Mail server communication |
| POP3 | Email retrieval concepts |
| IMAP | Remote mailbox access concepts |

---

# 🔍 Methodology

## 🌐 Phase 1 – HTTP Communication

The assessment began by manually connecting to an HTTP service using Telnet and constructing a valid HTTP/1.1 request.

This exercise demonstrated how web servers process requests at the protocol level and reinforced the importance of correctly formatted request headers.

---

## 📁 Phase 2 – FTP Interaction

Next, I connected to an FTP server and explored the authentication workflow used by the protocol.

The exercise demonstrated how FTP exchanges authentication credentials in cleartext and highlighted why secure alternatives such as FTPS and SFTP are preferred in modern environments.

---

## 📧 Phase 3 – SMTP Enumeration

Using Telnet, I connected directly to an SMTP service and inspected the server banner.

Banner grabbing provides valuable information about deployed services and software versions, helping security professionals understand the target environment during reconnaissance.

---

## 📬 Phase 4 – Email Protocols

The room introduced POP3 and IMAP, explaining how each protocol retrieves email while demonstrating why transmitting credentials over unencrypted channels creates unnecessary security risks.

---

## 🔒 Phase 5 – Secure Protocol Alternatives

The final section compared legacy cleartext protocols with their encrypted counterparts.

Examples included:

- HTTP → HTTPS
- FTP → FTPS / SFTP
- Telnet → SSH
- POP3 → POP3S
- IMAP → IMAPS
- SMTP → SMTPS / STARTTLS

This reinforced the importance of protecting credentials and application data while in transit.

---

# 🚨 Key Findings

| Severity | Finding | Impact |
|-----------|----------|--------|
| 🔴 High | Legacy protocols transmit credentials in cleartext | Increased risk of credential interception |
| 🟠 Medium | Service banners expose infrastructure information | Supports reconnaissance and fingerprinting |
| 🟢 Informational | Manual protocol interaction improves protocol understanding | Strengthens troubleshooting and penetration testing methodology |

---

# 🛡️ Best Practices Reinforced

- Prefer encrypted protocols whenever available.
- Avoid transmitting credentials over cleartext services.
- Validate exposed services through manual interaction when appropriate.
- Use banner grabbing responsibly during authorized assessments.
- Understand protocol behavior before relying on automated tools.

---

# 💡 What I Learned

This lab reinforced that understanding network protocols is fundamental to both penetration testing and defensive security. Interacting directly with services using Telnet provided a much deeper understanding of how application protocols operate compared to simply using graphical clients.

One of my biggest takeaways was recognizing that many legacy protocols transmit sensitive information—including usernames and passwords—in cleartext by default. Understanding these weaknesses makes it much easier to appreciate why modern environments rely on encrypted alternatives such as HTTPS, SSH, IMAPS, and SFTP.

---

# 📚 References

- TryHackMe – Protocols and Servers
- RFC 2616 / RFC 9110 – HTTP
- RFC 959 – FTP
- RFC 5321 – SMTP
- RFC 1939 – POP3
- RFC 3501 – IMAP

---

# ⚖️ Disclaimer

This documentation summarizes work completed within an authorized TryHackMe training environment for educational purposes only. The report focuses on networking concepts, protocol analysis, and professional documentation. Challenge answers and platform-specific solutions have intentionally been omitted.
