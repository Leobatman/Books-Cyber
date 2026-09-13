# Learning Roadmap

A structured progression from cybersecurity fundamentals to advanced offensive security, based on the books available in this collection.

This is not a generic roadmap — it maps directly to the books catalogued in this repository. Each stage lists the recommended reading in order.

---

## Visual Overview

```
                            ┌─────────────────────┐
                            │   FUNDAMENTALS      │
                            │                     │
                            │ • Hacking: Art of   │
                            │   Exploitation      │
                            │ • Basics of Hacking │
                            │   & Pentest         │
                            │ • CEH Study Guide   │
                            └────────┬────────────┘
                                     │
                    ┌────────────────┼────────────────┐
                    ▼                ▼                ▼
          ┌─────────────┐  ┌─────────────┐  ┌─────────────────┐
          │   LINUX     │  │  NETWORKING │  │  PROGRAMMING    │
          │             │  │             │  │                 │
          │ • Linux     │  │ • Hacking   │  │ • Python Crash  │
          │   Basics    │  │   Exposed   │  │   Course        │
          │   for       │  │ • Nmap      │  │ • Black Hat     │
          │   Hackers   │  │   Cookbook   │  │   Python        │
          │ • CompTIA   │  │ • Network   │  │ • Bash Shell    │
          │   Linux+    │  │   Scanning  │  │   Scripting     │
          └──────┬──────┘  └──────┬──────┘  └────────┬────────┘
                 │                │                   │
                 └────────────────┼───────────────────┘
                                  ▼
                     ┌────────────────────────┐
                     │    PENTESTING          │
                     │                        │
                     │ • Kali Linux Revealed  │
                     │ • Penetration Testing  │
                     │   (Weidman)            │
                     │ • Metasploit Guide     │
                     │ • Hacker Playbook 3    │
                     └───────────┬────────────┘
                                 │
                 ┌───────────────┼───────────────┐
                 ▼               ▼               ▼
        ┌──────────────┐ ┌─────────────┐ ┌─────────────────┐
        │ WEB SECURITY │ │  WINDOWS &  │ │  PRIVILEGE      │
        │              │ │  ACTIVE     │ │  ESCALATION     │
        │ • Web App    │ │  DIRECTORY  │ │                 │
        │   Hacker's   │ │             │ │ • Advanced      │
        │   Handbook   │ │ • Kali Win  │ │   Pentest       │
        │ • Bug Bounty │ │   Pentest   │ │   (Allsopp)     │
        │   Bootcamp   │ │ • AD Bypass │ │ • Mastering     │
        │ • Real-World │ │   Techniques│ │   Kali Adv.     │
        │   Bug Hunting│ │             │ │   Pentest       │
        │ • Browser    │ │             │ │                 │
        │   Hacker's HB│ │             │ │                 │
        └──────┬───────┘ └──────┬──────┘ └────────┬────────┘
               │                │                  │
               └────────────────┼──────────────────┘
                                ▼
                    ┌───────────────────────┐
                    │     RED TEAM          │
                    │                       │
                    │ • RTFM                │
                    │ • Red Teaming HB      │
                    │ • Practical AV        │
                    │   Evasion             │
                    │ • Cloud Pentest       │
                    │   for Red Teamers     │
                    └───────────┬───────────┘
                                │
                    ┌───────────┼───────────┐
                    ▼                       ▼
          ┌─────────────────┐    ┌──────────────────┐
          │ EXPLOIT         │    │ SPECIALIZATIONS  │
          │ DEVELOPMENT     │    │                  │
          │                 │    │ • Mobile Hacking │
          │ • Shellcoder's  │    │ • IoT Hacking    │
          │   Handbook      │    │ • SS7/Telecom    │
          │ • Violent Python │    │ • AI Security    │
          │ • JS for Hackers│    │ • Forensics      │
          └─────────────────┘    └──────────────────┘
```

---

## Stage 1: Foundations

**Goal:** Understand core concepts of cybersecurity, ethical hacking principles, and how systems work at a fundamental level.

**Duration:** 4-8 weeks

| Order | Book | Level | Priority | Notes |
|-------|------|-------|----------|-------|
| 1.1 | [Hacking: The Art of Exploitation](notes/hacking-the-art-of-exploitation.md) | Intermediate | ⭐⭐⭐⭐⭐ | Dense but foundational. Take your time with the C and assembly chapters. |
| 1.2 | [The Basics of Hacking and Penetration Testing](notes/basics-of-hacking-pentest.md) | Beginner | ⭐⭐⭐⭐ | Quick overview of the entire pentest methodology. Read this early. |
| 1.3 | CEH Certified Ethical Hacker All-in-One Exam Guide | Intermediate | ⭐⭐⭐⭐ | Broad coverage. Use as reference, not cover-to-cover reading. |
| 1.4 | Ghost in the Wires — Kevin Mitnick | Beginner | ⭐⭐⭐ | Not technical, but excellent for understanding social engineering mindset. |

**After this stage you should be able to:**
- Explain the penetration testing methodology (recon → scanning → exploitation → post-exploitation → reporting)
- Understand basic networking concepts (TCP/IP, DNS, ARP)
- Understand what ethical hacking means and its legal boundaries

---

## Stage 2: Operating Systems & Scripting

**Goal:** Become proficient in Linux (your primary offensive platform) and learn scripting for automation.

**Duration:** 4-6 weeks

| Order | Book | Level | Priority | Notes |
|-------|------|-------|----------|-------|
| 2.1 | [Linux Basics for Hackers](notes/linux-basics-for-hackers.md) | Beginner | ⭐⭐⭐⭐⭐ | Start here. Written specifically for security professionals. |
| 2.2 | [CompTIA Linux+ Study Guide](notes/comptia-linux-plus.md) | Beginner | ⭐⭐⭐⭐ | Deeper Linux admin knowledge. |
| 2.3 | Automate the Boring Stuff with Python | Beginner | ⭐⭐⭐ | If you're new to Python, start here before Black Hat Python. |
| 2.4 | [Bash Shell Scripting for Pentesters](notes/bash-shell-scripting-pentesters.md) | Intermediate | ⭐⭐⭐⭐ | Bash automation specifically for pentest workflows. |

**After this stage you should be able to:**
- Navigate Linux comfortably from the command line
- Write basic Bash and Python scripts
- Manage files, permissions, processes, and networking on Linux

---

## Stage 3: Networking & Scanning

**Goal:** Understand network protocols, learn reconnaissance and scanning techniques.

**Duration:** 3-5 weeks

| Order | Book | Level | Priority | Notes |
|-------|------|-------|----------|-------|
| 3.1 | [Hacking Exposed: Network Security Secrets & Solutions](notes/hacking-exposed-network-security.md) | Intermediate | ⭐⭐⭐⭐⭐ | The network hacking encyclopedia. Essential. |
| 3.2 | [Nmap Cookbook](notes/nmap-cookbook.md) | Beginner | ⭐⭐⭐⭐ | Practical, recipe-based approach to scanning. |
| 3.3 | [Kali Linux Network Scanning Cookbook](notes/kali-network-scanning-cookbook.md) | Intermediate | ⭐⭐⭐⭐ | Goes beyond Nmap into full network assessment. |

**After this stage you should be able to:**
- Perform network reconnaissance and enumeration
- Use Nmap effectively for host/service discovery
- Understand common network attack vectors

---

## Stage 4: Penetration Testing Core

**Goal:** Master the tools and methodology of professional penetration testing.

**Duration:** 8-12 weeks

| Order | Book | Level | Priority | Notes |
|-------|------|-------|----------|-------|
| 4.1 | [Kali Linux Revealed](notes/kali-linux-revealed.md) | Beginner | ⭐⭐⭐⭐⭐ | Know your platform inside out. |
| 4.2 | [Penetration Testing — Georgia Weidman](notes/penetration-testing-georgia-weidman.md) | Beginner | ⭐⭐⭐⭐⭐ | The best "first pentest book." Hands-on and practical. |
| 4.3 | [Metasploit: The Penetration Tester's Guide](notes/metasploit-penetration-testers-guide.md) | Intermediate | ⭐⭐⭐⭐⭐ | Master the most important exploitation framework. |
| 4.4 | [The Hacker Playbook 3](notes/the-hacker-playbook-3.md) | Intermediate | ⭐⭐⭐⭐⭐ | Real scenarios. Read after Weidman and Metasploit. |
| 4.5 | [Ethical Hacking and Penetration Testing Guide — Rafay Baloch](notes/ethical-hacking-pentest-guide-baloch.md) | Intermediate | ⭐⭐⭐⭐ | Good complement with different examples. |

**After this stage you should be able to:**
- Conduct a basic penetration test end-to-end
- Use Metasploit for exploitation and post-exploitation
- Write basic pentest reports

---

## Stage 5: Web Application Security

**Goal:** Deep dive into web application vulnerabilities, bug bounty methodology, and browser exploitation.

**Duration:** 6-10 weeks

| Order | Book | Level | Priority | Notes |
|-------|------|-------|----------|-------|
| 5.1 | [The Web Application Hacker's Handbook](notes/web-application-hackers-handbook.md) | Intermediate | ⭐⭐⭐⭐⭐ | The bible of web security. Read cover-to-cover. |
| 5.2 | [Bug Bounty Bootcamp](notes/bug-bounty-bootcamp.md) | Beginner | ⭐⭐⭐⭐⭐ | Modern, practical approach to finding real vulns. |
| 5.3 | [Real-World Bug Hunting](notes/real-world-bug-hunting.md) | Beginner | ⭐⭐⭐⭐⭐ | Learn from actual disclosed vulnerabilities. |
| 5.4 | [Bug Bounty Playbook (Ghostlulz)](notes/bug-bounty-playbook-ghostlulz.md) | Intermediate | ⭐⭐⭐⭐ | Practical methodology for bounty programs. |
| 5.5 | [JavaScript for Hackers](notes/javascript-for-hackers.md) | Advanced | ⭐⭐⭐⭐ | Essential for understanding XSS and browser attacks at depth. |
| 5.6 | [The Browser Hacker's Handbook](notes/browser-hackers-handbook.md) | Advanced | ⭐⭐⭐⭐ | Advanced browser exploitation with BeEF. |

**After this stage you should be able to:**
- Find and exploit OWASP Top 10 vulnerabilities
- Participate effectively in bug bounty programs
- Test APIs for security issues
- Understand client-side attacks

---

## Stage 6: Windows, Active Directory & Privilege Escalation

**Goal:** Attack Windows environments, Active Directory domains, and escalate privileges.

**Duration:** 4-6 weeks

| Order | Book | Level | Priority | Notes |
|-------|------|-------|----------|-------|
| 6.1 | [Kali Linux 2: Windows Penetration Testing](notes/kali-windows-penetration-testing.md) | Intermediate | ⭐⭐⭐⭐ | Windows-specific attack techniques. |
| 6.2 | AC DER BY PASS TECH (Active Directory Bypass Techniques) | Advanced | ⭐⭐⭐ | Focused on AD evasion and bypass. |
| 6.3 | [Advanced Penetration Testing — Wil Allsopp](notes/advanced-penetration-testing-allsopp.md) | Advanced | ⭐⭐⭐⭐ | Multi-vector attacks including privilege escalation chains. |
| 6.4 | [Mastering Kali Linux for Advanced Penetration Testing](notes/mastering-kali-advanced-pentest.md) | Advanced | ⭐⭐⭐⭐ | Includes post-exploitation and lateral movement. |

**After this stage you should be able to:**
- Attack and enumerate Active Directory environments
- Perform privilege escalation on Windows and Linux
- Understand lateral movement techniques

---

## Stage 7: Red Team Operations

**Goal:** Conduct full adversary simulation operations with evasion and stealth.

**Duration:** 4-8 weeks

| Order | Book | Level | Priority | Notes |
|-------|------|-------|----------|-------|
| 7.1 | [RTFM: Red Team Field Manual](notes/rtfm-red-team-field-manual.md) | Advanced | ⭐⭐⭐⭐⭐ | Your quick reference during operations. |
| 7.2 | [Red Teaming Handbook (UK MoD)](notes/red-teaming-handbook.md) | Intermediate | ⭐⭐⭐⭐ | Strategic perspective on red teaming. |
| 7.3 | [Practical Anti-virus Evasion](notes/practical-antivirus-evasion.md) | Advanced | ⭐⭐⭐⭐ | Critical for real-world engagements. |
| 7.4 | [Cloud Penetration Testing for Red Teamers](notes/cloud-pentest-red-teamers.md) | Advanced | ⭐⭐⭐⭐ | Modern cloud attack techniques. |
| 7.5 | [Black Hat Python](notes/black-hat-python.md) | Intermediate | ⭐⭐⭐⭐⭐ | Build custom tools for your operations. |

**After this stage you should be able to:**
- Plan and execute red team engagements
- Evade antivirus and endpoint detection
- Attack cloud environments
- Build custom offensive tools

---

## Stage 8: Advanced Offensive Security

**Goal:** Deep specialization in exploit development, reverse engineering, and cutting-edge techniques.

**Duration:** Ongoing

| Order | Book | Level | Priority | Notes |
|-------|------|-------|----------|-------|
| 8.1 | [The Shellcoder's Handbook](notes/shellcoders-handbook.md) | Expert | ⭐⭐⭐⭐⭐ | The definitive guide to exploit writing. |
| 8.2 | [Violent Python](notes/violent-python.md) | Intermediate | ⭐⭐⭐⭐ | Offensive Python recipes. |
| 8.3 | [Creatively Malicious Prompt Engineering](notes/creatively-malicious-prompt-engineering.md) | Advanced | ⭐⭐⭐⭐ | Emerging attack surface in AI systems. |

---

## Specialization Tracks

After completing the core path (Stages 1-7), pursue specializations based on your interests:

| Track | Key Books | Category |
|-------|-----------|----------|
| **Mobile Hacking** | Android Hacker's Handbook, iOS Hacker's Handbook, Mobile App Hacker's Handbook | [10-mobile-iot-hacking](10-mobile-iot-hacking/) |
| **IoT & Containers** | IoT Hacker's Handbook, Hacking Kubernetes | [10-mobile-iot-hacking](10-mobile-iot-hacking/) |
| **Telecom/SS7** | SS7: Locate. Track. Manipulate., SS7 Security Report, Hacking Mobile Networks via SS7 | [13-telecom-ss7](13-telecom-ss7/) |
| **Digital Forensics** | CHFI v01, CHFI v03 | [11-digital-forensics](11-digital-forensics/) |
| **Blue Team** | Blue Team Cheat Sheet, MITRE ATT&CK reference, 100 SOC Tools | [12-blue-team-soc](12-blue-team-soc/) |
| **AI Security** | AI Tools in Cybersecurity, Creatively Malicious Prompt Engineering | [14-ai-cybersecurity](14-ai-cybersecurity/) |

---

## Certifications Alignment

| Certification | Most Relevant Books from This Collection |
|--------------|------------------------------------------|
| **CEH** | CEH All-in-One Exam Guide, CEH v10 Study Guide, CEH Foundation Guide |
| **OSCP** | Penetration Testing (Weidman), Hacker Playbook 3, Kali Linux Revealed, Linux Basics for Hackers |
| **CISSP** | CISSP For Dummies, Cybersecurity Strategies and Best Practices |
| **CISM** | Complete Guide to CISM Certification |
| **CHFI** | CHFI v01, CHFI v03 |
| **CompTIA Linux+** | CompTIA Linux+ Study Guide (XK0-004) |

---

*This roadmap is a living document. As new books are added to the collection, it will be updated to reflect the best available learning paths.*
