# 🛡️ Passive Reconnaissance

> *A reconnaissance-focused lab completed as part of the TryHackMe Penetration Tester learning path, introducing passive information gathering techniques used during the early stages of penetration testing.*

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
| 🔎 Category | Passive Reconnaissance |
| 📅 Completed | 15th July 2026 |
| 📈 Status | Completed |

---

# 🎯 Why I Completed This Lab

As part of my penetration testing learning journey, I completed this lab to strengthen my understanding of passive reconnaissance techniques and their role during the information gathering phase of a security assessment.

Unlike active reconnaissance, passive reconnaissance allows security professionals to collect valuable intelligence without directly interacting with the target, reducing the likelihood of detection while building a comprehensive understanding of the attack surface.

---

# 🚀 Objective

Develop a practical understanding of passive reconnaissance by:

- Understanding the importance of information gathering.
- Enumerating DNS records using industry-standard tools.
- Identifying publicly available infrastructure information.
- Practicing scope-aware reconnaissance.
- Building a foundation for later enumeration and exploitation phases.

---

# ⚡ Passive Reconnaissance Workflow

```text
Target Identification
        │
        ▼
DNS Enumeration
        │
        ▼
Infrastructure Discovery
        │
        ▼
Information Analysis
        │
        ▼
Attack Surface Mapping
        │
        ▼
Reporting
```

---

# 🧠 Skills Practiced

- ✅ Passive Reconnaissance
- ✅ DNS Enumeration
- ✅ DNS Record Analysis
- ✅ OSINT Fundamentals
- ✅ Scope Validation
- ✅ Infrastructure Discovery
- ✅ Information Gathering
- ✅ Technical Documentation

---

# 🛠️ Technologies & Tools

| Tool | Purpose |
|------|---------|
| dig | DNS record enumeration |
| nslookup | DNS querying and validation |
| Public DNS Servers | Name resolution and verification |
| DNS Records | A, MX, TXT record analysis |

---

# 🔍 Methodology

## 🌐 Phase 1 – Target Identification

The assessment began by identifying the target domains and establishing the scope of the reconnaissance exercise. Emphasis was placed on maintaining scope discipline throughout the assessment and avoiding unnecessary enumeration outside the authorized environment.

---

## 🔎 Phase 2 – DNS Enumeration

Using both **dig** and **nslookup**, I queried multiple DNS record types to identify publicly available information about the target.

The exercise included:

- A Records
- MX Records
- TXT Records

Using multiple tools reinforced the importance of validating results while becoming familiar with common DNS enumeration workflows used during penetration testing engagements.

---

## 📝 Phase 3 – Information Analysis

The retrieved DNS records were analyzed to better understand the target's publicly exposed infrastructure.

Particular attention was given to TXT records, demonstrating how organizations may unintentionally expose useful information through publicly accessible DNS data.

The lab reinforced how passive reconnaissance can reveal valuable intelligence before any active interaction with a target system.

---

## 🗂️ Phase 4 – Scope Awareness

An important lesson throughout the exercise was maintaining strict assessment scope.

Professional penetration tests require analysts to gather information only from authorized targets. Remaining within scope ensures findings remain relevant while avoiding unnecessary or unauthorized reconnaissance.

---

## 📄 Phase 5 – Reporting

The final stage focused on documenting collected information, methodology, and observations in a structured format suitable for future assessment phases.

Well-organized reconnaissance findings provide the foundation for subsequent enumeration, vulnerability assessment, and exploitation activities.

---

# 🚨 Key Findings

| Severity | Finding | Impact |
|-----------|----------|--------|
| 🟢 Informational | Public DNS records exposed | Enabled infrastructure discovery through passive reconnaissance |
| 🟢 Informational | Multiple DNS record types identified | Improved understanding of target services |
| 🟢 Informational | Scope discipline reinforced | Ensured reconnaissance remained focused and authorized |

---

# 🛡️ Best Practices Reinforced

- Define assessment scope before reconnaissance.
- Prefer passive information gathering before active scanning.
- Validate DNS information using multiple tools.
- Document discovered infrastructure for later assessment phases.
- Minimize unnecessary interaction with production systems during early reconnaissance.

---

# 💡 What I Learned

This lab reinforced that successful penetration testing begins long before exploitation. Passive reconnaissance provides valuable intelligence while minimizing the likelihood of detection, making it one of the most important phases of an engagement.

I also gained more confidence using common DNS enumeration tools such as **dig** and **nslookup**, understanding how different record types contribute to mapping an organization's publicly exposed infrastructure. Finally, the exercise highlighted the importance of maintaining strict scope throughout every assessment to ensure findings remain relevant, ethical, and professionally conducted.

---

# 📚 References

- TryHackMe – Passive Reconnaissance
- RFC 1034 & RFC 1035 – Domain Name System (DNS)
- ISC BIND Documentation
- DNSDumpster

---

# ⚖️ Disclaimer

This documentation summarizes work completed within an authorized TryHackMe training environment for educational purposes only. The report focuses on reconnaissance methodology, DNS enumeration, and professional documentation. Challenge answers and platform-specific solutions have intentionally been omitted.
