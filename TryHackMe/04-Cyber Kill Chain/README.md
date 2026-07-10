# 🛡️ Cyber Kill Chain

> *A defensive security lab completed as part of the TryHackMe learning platform, exploring the Lockheed Martin Cyber Kill Chain Framework and how attackers progress through each stage of a cyber intrusion.*

![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![Platform](https://img.shields.io/badge/Platform-TryHackMe-red)
![Category](https://img.shields.io/badge/Category-Threat%20Intelligence-blue)
![Framework](https://img.shields.io/badge/Framework-Cyber%20Kill%20Chain-orange)

---

## 📋 Lab Information

| Property | Details |
|-----------|---------|
| 🎯 Platform | TryHackMe |
| 🛡️ Category | Threat Intelligence & Defensive Security |
| 📚 Framework | Lockheed Martin Cyber Kill Chain |
| 📅 Completed | 10th July 2026 |
| 📈 Status | Completed |

---

# 🎯 Why I Completed This Lab

As part of my cybersecurity learning journey, I completed this room to better understand how attackers execute real-world cyber intrusions and how defenders can identify opportunities to detect, disrupt, and contain attacks throughout their lifecycle.

Rather than focusing on individual exploits, this lab introduced the complete attack lifecycle, helping me understand how offensive techniques, threat intelligence, and defensive strategies connect throughout an engagement.

---

# 🚀 Objective

Develop a practical understanding of the Lockheed Martin Cyber Kill Chain by:

- Understanding each stage of a cyber attack.
- Learning common attacker techniques throughout the intrusion lifecycle.
- Recognizing defensive opportunities to interrupt attacks.
- Mapping attacker behaviors to each phase of the framework.
- Strengthening incident response and threat hunting methodologies.

---

# ⚡ Cyber Kill Chain Workflow

```text
Reconnaissance
       │
       ▼
Weaponization
       │
       ▼
Delivery
       │
       ▼
Exploitation
       │
       ▼
Installation
       │
       ▼
Command & Control
       │
       ▼
Actions on Objectives
```

---

# 🧠 Skills Practiced

- ✅ Threat Intelligence
- ✅ Cyber Kill Chain Analysis
- ✅ Attack Lifecycle Mapping
- ✅ Incident Response Concepts
- ✅ Threat Hunting Methodology
- ✅ Defensive Security
- ✅ Persistence Identification
- ✅ Command & Control Analysis

---

# 🛠️ Technologies & Concepts

| Technology / Concept | Purpose |
|----------------------|---------|
| Cyber Kill Chain | Understanding attacker progression |
| OSINT | Information gathering |
| DNS Enumeration | Reconnaissance |
| Spear Phishing | Initial payload delivery |
| Malware | Payload execution |
| PowerShell | Post-exploitation |
| DNS Tunneling | Command & Control |
| HTTP/HTTPS Beaconing | C2 Communications |
| Persistence Mechanisms | Long-term access |
| Data Exfiltration | Objective completion |

---

# 🔍 Methodology

## 🌐 Phase 1 – Reconnaissance

The lab began by exploring how attackers collect publicly available information before launching an attack. This included techniques such as OSINT, DNS enumeration, WHOIS lookups, social media profiling, and technology fingerprinting.

The exercise reinforced how thorough reconnaissance improves the likelihood of a successful intrusion.

---

## 🛠️ Phase 2 – Weaponization

Next, I explored how attackers prepare malicious payloads tailored to their target environment.

The room introduced concepts including malware creation, exploit selection, Office document macros, Remote Access Trojans (RATs), and malicious scripting while clearly distinguishing between exploits, payloads, and malware.

---

## 📨 Phase 3 – Delivery

This phase focused on the methods attackers use to deliver malicious content to victims.

Examples included spear phishing, malicious email attachments, drive-by downloads, watering hole attacks, USB-based attacks, and malvertising.

The exercise highlighted why phishing continues to be one of the most successful attack vectors.

---

## 💥 Phase 4 – Exploitation

I explored how attackers achieve code execution after successful delivery by exploiting software vulnerabilities or manipulating user behavior.

The room introduced concepts such as remote code execution, memory corruption, browser exploitation, zero-day vulnerabilities, and social engineering techniques.

---

## ⚙️ Phase 5 – Installation

Following exploitation, the focus shifted toward persistence.

The lab demonstrated common persistence mechanisms including registry modifications, scheduled tasks, startup persistence, backdoors, malware installation, and dynamic linker hijacking.

Understanding persistence emphasized how attackers maintain access even after system reboots.

---

## 📡 Phase 6 – Command & Control (C2)

This section introduced how compromised systems establish communication with attacker-controlled infrastructure.

Topics included:

- HTTP/HTTPS beaconing
- DNS tunneling
- Reverse shells
- Encrypted communications
- Beacon intervals
- Fallback communication channels

The lab reinforced how defenders monitor outbound traffic to identify compromised hosts.

---

## 🎯 Phase 7 – Actions on Objectives

The final phase examined attacker objectives after compromise.

Examples included:

- Credential theft
- Privilege escalation
- Internal reconnaissance
- Lateral movement
- Data exfiltration
- Ransomware deployment
- Backup deletion
- System destruction

This demonstrated that initial compromise is often only the beginning of a larger attack.

---

# 🧪 Practical Exercise

The lab concluded with an interactive scenario requiring real-world attacker techniques to be mapped to the correct Cyber Kill Chain phase.

Activities included classifying:

- Spear phishing attachments
- Public-facing application exploitation
- PowerShell execution
- Dynamic linker hijacking
- Command & Control fallback channels
- Data collection from compromised systems

This practical exercise strengthened my understanding of how attacks evolve across multiple stages rather than occurring as isolated events.

---

# 🚨 Defensive Skills Developed

- Understanding attacker methodology
- Mapping attacks across the Cyber Kill Chain
- Threat hunting fundamentals
- Identifying persistence mechanisms
- Recognizing Command & Control traffic
- Strengthening incident response workflows
- Relating attacker behavior to defensive controls

---

# 🛡️ Defensive Opportunities

| Kill Chain Stage | Example Defensive Controls |
|------------------|----------------------------|
| Reconnaissance | Attack surface reduction, OSINT monitoring |
| Weaponization | Threat intelligence, malware analysis |
| Delivery | Email security, web filtering, user awareness |
| Exploitation | Patch management, vulnerability management |
| Installation | Endpoint Detection & Response (EDR), application control |
| Command & Control | Network monitoring, IDS/IPS, DNS analysis |
| Actions on Objectives | Least privilege, segmentation, DLP, incident response |

---

# 💡 What I Learned

This room significantly improved my understanding of how cyber attacks develop from initial reconnaissance through to achieving an attacker's objectives. Rather than viewing attacks as isolated events, I learned to analyze them as a structured sequence of phases where defenders have multiple opportunities to detect, delay, or completely prevent compromise.

One of my biggest takeaways was that effective cybersecurity is not solely about responding after an incident occurs. Understanding attacker methodology enables defenders to proactively identify weak points, strengthen security controls, and improve threat hunting and incident response capabilities.

---

# 📚 References

- TryHackMe – Cyber Kill Chain
- Lockheed Martin Cyber Kill Chain Framework
- MITRE ATT&CK Framework
- NIST Cybersecurity Framework

---

# ⚖️ Disclaimer

This documentation summarizes work completed within an authorized TryHackMe training environment for educational purposes only. The report focuses on cybersecurity concepts, defensive methodology, and professional documentation. Challenge answers and platform-specific solutions have intentionally been omitted.
