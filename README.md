# Cybersecurity Books & Learning Resources

A curated, organized collection of cybersecurity book references, study notes, and learning paths focused on **Offensive Security**, **Penetration Testing**, **Red Teaming**, and related disciplines.

This repository serves as a structured study guide for anyone pursuing a career or deepening their knowledge in cybersecurity. It contains **120+ book references** organized by topic and difficulty, with original study notes, priority ratings, and recommended learning sequences.

> **Note:** This repository does not host or distribute any copyrighted material. It contains only original notes, reviews, metadata, and study recommendations. All book rights belong to their respective authors and publishers.

---

## Table of Contents

- [About This Project](#about-this-project)
- [Who Is This For](#who-is-this-for)
- [Repository Structure](#repository-structure)
- [Categories](#categories)
- [Priority Ratings](#priority-ratings)
- [Quick Start by Level](#quick-start-by-level)
- [Learning Paths](#learning-paths)
- [Book Catalog](#book-catalog)
- [Technologies Covered](#technologies-covered)
- [How to Use This Repository](#how-to-use-this-repository)
- [Copyright & Licensing](#copyright--licensing)
- [Contributing](#contributing)
- [Disclaimer](#disclaimer)

---

## About This Project

This project was born from the need to organize a growing collection of cybersecurity books into something actionable — not just a pile of PDFs, but a structured curriculum.

**Goals:**
- Provide a clear, opinionated roadmap for cybersecurity self-study.
- Catalog books with honest assessments of their strengths, weaknesses, and relevance.
- Help learners avoid wasting time on outdated or low-quality material.
- Serve as a reference for building reading lists by specialization.

**This is not:**
- A piracy repository. No books are hosted here.
- A generic "awesome list" with no commentary. Every entry is reviewed.
- A certification study guide (though many cert-relevant books are included).

---

## Who Is This For

| Audience | What You'll Find |
|----------|-----------------|
| **Beginners** starting in cybersecurity | Foundational book recommendations and a step-by-step roadmap |
| **Students** preparing for certs (CEH, OSCP, CISSP) | Relevant study material organized by topic |
| **Pentesters** looking for practical references | Hands-on books rated by real-world applicability |
| **Red Teamers** building their toolkit | Advanced offensive security resources and techniques |
| **Bug Bounty Hunters** | Web security and vulnerability hunting references |
| **Blue Teamers / SOC Analysts** | Defensive resources, forensics, and detection guides |
| **Developers** interested in security | Programming-focused security books (Python, JavaScript) |

---

## Repository Structure

```
cybersecurity-books/
├── README.md               ← You are here
├── CATALOG.md              ← Complete book catalog (sortable table)
├── ROADMAP.md              ← Visual learning roadmap
├── CONTRIBUTING.md         ← How to contribute
├── LICENSE                 ← CC BY-NC-SA 4.0 (original content only)
│
├── 01-fundamentals/        ← Security foundations, certifications
├── 02-network-security/    ← Network attacks, scanning, DDoS
├── 03-linux/               ← Linux administration & security
├── 04-windows-active-directory/ ← Windows hacking, AD attacks
├── 05-web-security/        ← Web apps, bug bounty, XSS, API security
├── 06-pentesting/          ← Penetration testing methodology & tools
├── 07-red-team/            ← Red team operations, evasion, C2
├── 08-programming-for-security/ ← Python, Bash, JS for hackers
├── 09-exploit-development/ ← Shellcode, buffer overflows, binary exploitation
├── 10-mobile-iot-hacking/  ← Mobile, IoT, containers, VoIP
├── 11-digital-forensics/   ← Incident response, forensic analysis
├── 12-blue-team-soc/       ← SOC operations, MITRE ATT&CK, detection
├── 13-telecom-ss7/         ← SS7 protocol security, telecom attacks
├── 14-ai-cybersecurity/    ← AI/ML in security, prompt injection
│
├── paths/                  ← Structured learning paths by specialization
│   ├── offensive-security-path.md
│   ├── web-security-path.md
│   └── blue-team-path.md
│
└── notes/                  ← Individual book study notes
    ├── README.md           ← Notes index
    └── *.md                ← One file per book (⭐⭐⭐+)
```

---

## Categories

| # | Category | Books | Focus |
|---|----------|-------|-------|
| 01 | [Fundamentals](01-fundamentals/) | 17 | Security foundations, ethical hacking concepts, certifications |
| 02 | [Network Security](02-network-security/) | 9 | Network attacks, scanning, protocol exploitation |
| 03 | [Linux](03-linux/) | 4 | Linux admin, Bash scripting, system security |
| 04 | [Windows & Active Directory](04-windows-active-directory/) | 2 | Windows exploitation, AD attack paths |
| 05 | [Web Security](05-web-security/) | 19 | Web application hacking, bug bounty, API security |
| 06 | [Pentesting](06-pentesting/) | 20 | Penetration testing tools, methodology, Kali Linux |
| 07 | [Red Team](07-red-team/) | 5 | Red team operations, evasion, cloud attacks |
| 08 | [Programming for Security](08-programming-for-security/) | 11 | Python, Bash, JavaScript for offensive security |
| 09 | [Exploit Development](09-exploit-development/) | 2 | Shellcode, binary exploitation, vulnerability research |
| 10 | [Mobile & IoT Hacking](10-mobile-iot-hacking/) | 8 | Mobile apps, IoT, containers, platform-specific attacks |
| 11 | [Digital Forensics](11-digital-forensics/) | 2 | Computer forensics, incident response |
| 12 | [Blue Team & SOC](12-blue-team-soc/) | 4 | SOC tools, MITRE ATT&CK, threat detection |
| 13 | [Telecom & SS7](13-telecom-ss7/) | 11 | SS7 protocol security, mobile network attacks |
| 14 | [AI & Cybersecurity](14-ai-cybersecurity/) | 3 | AI-powered security tools, prompt injection |

---

## Priority Ratings

| Rating | Meaning | Action |
|--------|---------|--------|
| ⭐⭐⭐⭐⭐ | **Essential** | Must-read. Foundational for the topic. |
| ⭐⭐⭐⭐ | **Highly Recommended** | Excellent depth or unique coverage. |
| ⭐⭐⭐ | **Recommended** | Solid reference, good for specific topics. |
| ⭐⭐ | **Complementary** | Useful as secondary reading. |
| ⭐ | **Optional** | Niche, outdated, or redundant with better alternatives. |

---

## Quick Start by Level

### Beginner — Start Here

| # | Book | Category | Why |
|---|------|----------|-----|
| 1 | Linux Basics for Hackers — OccupyTheWeb | Linux | Learn the OS you'll live in |
| 2 | The Basics of Hacking and Penetration Testing — Engebretson | Fundamentals | Concise intro to methodology |
| 3 | Kali Linux Revealed — Aharoni, Hertzog | Pentesting | Master your primary tool |
| 4 | Nmap Cookbook — Nicholas Marsh | Network Security | Learn to scan and enumerate |
| 5 | Bug Bounty Bootcamp | Web Security | Practical web vulnerability hunting |

### Intermediate — Build Depth

| # | Book | Category | Why |
|---|------|----------|-----|
| 1 | Hacking: The Art of Exploitation — Erickson | Fundamentals | Understand exploitation at a deeper level |
| 2 | Penetration Testing — Georgia Weidman | Pentesting | Comprehensive hands-on methodology |
| 3 | The Hacker Playbook 3 — Peter Kim | Pentesting | Real-world pentest scenarios |
| 4 | The Web Application Hacker's Handbook — Stuttard | Web Security | The definitive web security reference |
| 5 | Black Hat Python — Justin Seitz | Programming | Build your own offensive tools |
| 6 | Metasploit: The Penetration Tester's Guide — Kennedy | Pentesting | Master the most used exploitation framework |

### Advanced — Specialize

| # | Book | Category | Why |
|---|------|----------|-----|
| 1 | RTFM: Red Team Field Manual — Ben Clark | Red Team | Essential quick reference for operations |
| 2 | The Shellcoder's Handbook — Anley et al. | Exploit Dev | Deep binary exploitation |
| 3 | Advanced Penetration Testing — Wil Allsopp | Pentesting | Complex, multi-vector attack chains |
| 4 | The Browser Hacker's Handbook — Alcorn et al. | Web Security | Advanced browser exploitation |
| 5 | Hacking Exposed: Network Security — Scambray et al. | Network Security | Comprehensive network attack encyclopedia |

---

## Learning Paths

Structured sequences for different career goals:

- **[Offensive Security Path](paths/offensive-security-path.md)** — From zero to pentest/red team professional
- **[Web Security Path](paths/web-security-path.md)** — Specialization in web application security and bug bounty
- **[Blue Team Path](paths/blue-team-path.md)** — Defensive security, SOC operations, and forensics

See also: [ROADMAP.md](ROADMAP.md) for the complete visual learning roadmap.

---

## Book Catalog

The complete catalog with all 120+ books is available in **[CATALOG.md](CATALOG.md)**.

It includes: title, author, category, level, priority rating, and key topics for every book in the collection.

---

## Technologies Covered

| Area | Technologies & Tools |
|------|---------------------|
| **Operating Systems** | Kali Linux, Ubuntu, Windows Server, macOS, Android, iOS |
| **Frameworks** | Metasploit, Cobalt Strike, Empire, Burp Suite |
| **Scanning** | Nmap, Nessus, Nikto, Masscan, OpenVAS |
| **Web Testing** | OWASP ZAP, Burp Suite, SQLMap, XSSer, DirBuster |
| **Programming** | Python 3, Bash, JavaScript, PowerShell, C/C++ |
| **Networking** | TCP/IP, DNS, ARP, SS7, VoIP/SIP, BGP |
| **Exploitation** | Buffer overflows, ROP chains, shellcode, heap spraying |
| **Post-Exploitation** | Mimikatz, BloodHound, Rubeus, PowerView |
| **Forensics** | Autopsy, Volatility, FTK, EnCase |
| **Containers** | Docker, Kubernetes |
| **Cloud** | AWS, Azure, GCP security |
| **AI/ML** | LLM security, prompt injection, adversarial ML |

---

## How to Use This Repository

1. **Assess your level.** Check the [Quick Start by Level](#quick-start-by-level) section.
2. **Pick a path.** Choose a [learning path](paths/) that matches your goals.
3. **Read the notes.** Before starting a book, read its [study note](notes/) for context, prerequisites, and tips.
4. **Follow the roadmap.** Use [ROADMAP.md](ROADMAP.md) to understand where each book fits in the bigger picture.
5. **Acquire the books legally.** Official links are provided in each book's study note when available.
6. **Take your own notes.** Fork this repo and add your personal notes as you progress.

---

## Copyright & Licensing

**Original content** in this repository (notes, reviews, study guides, roadmaps, and organization) is licensed under [CC BY-NC-SA 4.0](LICENSE).

**Books and publications** referenced here are the intellectual property of their respective authors and publishers. This repository:

- Does **not** host, distribute, or link to unauthorized copies of any book.
- Provides only metadata, original commentary, and study recommendations.
- Uses book information under fair use for educational review and commentary.

If you are a rights holder with concerns, please open an issue.

---

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines on:
- Adding new book entries
- Improving study notes
- Suggesting learning paths
- Reporting errors

---

## Disclaimer

This repository is intended for **educational purposes only**. The books and techniques referenced here should be used exclusively in authorized, legal contexts such as:

- Authorized penetration testing engagements
- Capture The Flag (CTF) competitions
- Personal lab environments
- Academic research

Unauthorized access to computer systems is illegal. The repository owner is not responsible for any misuse of the information referenced here.

---

*Last updated: September 2026*
