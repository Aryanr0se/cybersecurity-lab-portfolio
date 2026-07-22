# 🛡️ Walking An Application

> *A web application security lab completed as part of the TryHackMe Penetration Tester learning path, focusing on manual web application reconnaissance using browser-based techniques and developer tools.*

![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![Platform](https://img.shields.io/badge/Platform-TryHackMe-red)
![Category](https://img.shields.io/badge/Category-Web%20Security-blue)
![Learning Path](https://img.shields.io/badge/Path-Penetration%20Tester-orange)

---

## 📋 Lab Information

| Property | Details |
|-----------|---------|
| 🎯 Platform | TryHackMe |
| 🛣️ Learning Path | Penetration Tester |
| 🌐 Category | Web Application Security |
| 📅 Completed | 22nd July 2026 |
| 📈 Status | Completed |

---

# 🎯 Why I Completed This Lab

As part of my penetration testing learning journey, I completed this lab to strengthen my understanding of manual web application assessment. Before relying on automated scanners, it's important to understand how an application behaves by interacting with it directly and observing what information is exposed through the browser.

This room reinforced that effective web application testing starts with curiosity, careful observation, and understanding how users interact with an application.

---

# 🚀 Objective

Develop practical experience with manual web application reconnaissance by:

- Exploring application functionality through normal user interaction.
- Identifying exposed information within HTML source code.
- Using browser Developer Tools to inspect client-side behavior.
- Understanding how authentication and session management work.
- Building a structured methodology for manual application assessment.

---

# ⚡ Manual Assessment Workflow

```text
Application Discovery
        │
        ▼
Browse Application
        │
        ▼
Review Source Code
        │
        ▼
Inspect Developer Tools
        │
        ▼
Analyze Requests & Storage
        │
        ▼
Identify Potential Attack Surface
```

---

# 🧠 Skills Practiced

- ✅ Manual Web Reconnaissance
- ✅ Application Mapping
- ✅ HTML Source Analysis
- ✅ Browser Developer Tools
- ✅ Authentication Workflow Analysis
- ✅ Client-Side Inspection
- ✅ Session Analysis
- ✅ Security Observation

---

# 🛠️ Technologies & Tools

| Tool | Purpose |
|------|---------|
| Web Browser | Manual application interaction |
| Developer Tools | Inspect HTML, CSS, JavaScript, and network traffic |
| Inspector | Analyze page structure and DOM |
| Network Panel | Review HTTP requests and responses |
| Storage Panel | Examine cookies and browser storage |
| Debugger | Analyze client-side JavaScript |

---

# 🔍 Methodology

## 🌐 Phase 1 – Application Exploration

The assessment began by navigating the application as a legitimate user to understand its structure, available functionality, and user workflows. This included exploring accessible pages and interacting with common features before attempting deeper analysis.

---

## 👤 Phase 2 – Authentication Assessment

I created a user account and observed the application's authentication process, providing insight into registration, login behavior, and authenticated functionality.

Understanding normal application workflows establishes a baseline before evaluating security controls.

---

## 📄 Phase 3 – Source Code Review

The lab emphasized reviewing HTML source code for information that is not immediately visible within the rendered page.

Manual source inspection can reveal hidden links, developer comments, application metadata, and implementation details that contribute to a broader understanding of the application's attack surface.

---

## 🛠️ Phase 4 – Developer Tools Analysis

Using the browser's Developer Tools, I examined:

- HTML structure using the Inspector
- JavaScript behavior through the Debugger
- Network requests and responses
- Cookies and browser storage
- Client-side resources loaded by the application

These observations provided valuable insight into how the application functions behind the scenes.

---

## 📝 Phase 5 – Manual Security Assessment

Rather than relying on automated scanners, the final stage focused on building a complete picture of the application's functionality through careful observation, logical reasoning, and systematic exploration.

This methodology helps identify potential weaknesses while developing a stronger understanding of modern web applications.

---

# 🚨 Key Findings

| Severity | Finding | Impact |
|-----------|----------|--------|
| 🟢 Informational | Manual browsing revealed application structure | Improved understanding of application workflow |
| 🟢 Informational | Source code exposed implementation details | Supported further reconnaissance |
| 🟢 Informational | Developer Tools provided visibility into client-side behavior | Enhanced understanding of requests, storage, and application logic |

---

# 🛡️ Best Practices Reinforced

- Explore applications manually before using automated tools.
- Review HTML source for hidden information and implementation details.
- Use Developer Tools to inspect requests, storage, and client-side behavior.
- Map application functionality before testing individual features.
- Document observations throughout the assessment.

---

# 💡 What I Learned

This lab reinforced that some of the most valuable findings come from careful observation rather than automated scanning. Walking through an application manually provides context that scanners often cannot, helping identify hidden functionality, understand authentication workflows, and recognize how client-side components interact with the server.

One of my biggest takeaways was realizing how much information is openly available through browser Developer Tools. Understanding network requests, page structure, cookies, and client-side resources provides a much stronger foundation before moving into vulnerability testing with specialized tools.

---

# 📚 References

- TryHackMe – Walking An Application
- Mozilla Developer Network (MDN) – Browser Developer Tools
- OWASP Web Security Testing Guide (WSTG)

---

# ⚖️ Disclaimer

This documentation summarizes work completed within an authorized TryHackMe training environment for educational purposes only. The report focuses on manual web application assessment methodology, browser-based analysis, and professional documentation. Challenge answers and platform-specific solutions have intentionally been omitted.
