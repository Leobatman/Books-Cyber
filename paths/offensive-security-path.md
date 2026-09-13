# Offensive Security Learning Path

A structured path from beginner to advanced offensive security professional. This path covers pentesting, red teaming, web security, Active Directory attacks, privilege escalation, and exploit development.

Follow this path if your goal is to work as a penetration tester, red team operator, or offensive security consultant.

---

## Prerequisites

- Basic understanding of how computers work
- Willingness to set up a home lab (VMs, vulnerable machines)
- Time commitment: 12-18 months for the full path

---

## Phase 1: Foundations (Weeks 1-8)

**Objective:** Build a solid base in security concepts, Linux, and programming.

| Step | Book | Time | What You'll Learn |
|------|------|------|-------------------|
| 1 | [Linux Basics for Hackers](../notes/linux-basics-for-hackers.md) | 2-3 weeks | CLI, filesystem, permissions, networking, Bash |
| 2 | [The Basics of Hacking and Penetration Testing](../notes/basics-of-hacking-pentest.md) | 1-2 weeks | Pentest methodology overview |
| 3 | [Hacking: The Art of Exploitation](../notes/hacking-the-art-of-exploitation.md) | 3-4 weeks | C, assembly, buffer overflows, networking internals |

**Lab work:** Install Kali Linux in a VM. Practice basic commands daily.

---

## Phase 2: Scanning & Networking (Weeks 9-13)

**Objective:** Master network reconnaissance and scanning.

| Step | Book | Time | What You'll Learn |
|------|------|------|-------------------|
| 4 | [Nmap Cookbook](../notes/nmap-cookbook.md) | 1-2 weeks | Host/port/service scanning |
| 5 | [Hacking Exposed: Network Security](../notes/hacking-exposed-network-security.md) | 2-3 weeks | Network attack encyclopedia |

**Lab work:** Scan your own lab network. Set up vulnerable VMs (Metasploitable, VulnHub machines).

---

## Phase 3: Core Pentesting (Weeks 14-26)

**Objective:** Conduct end-to-end penetration tests.

| Step | Book | Time | What You'll Learn |
|------|------|------|-------------------|
| 6 | [Kali Linux Revealed](../notes/kali-linux-revealed.md) | 1-2 weeks | Know your platform deeply |
| 7 | [Penetration Testing — Georgia Weidman](../notes/penetration-testing-georgia-weidman.md) | 3-4 weeks | Full pentest lifecycle |
| 8 | [Metasploit: The Penetration Tester's Guide](../notes/metasploit-penetration-testers-guide.md) | 2-3 weeks | Metasploit mastery |
| 9 | [The Hacker Playbook 3](../notes/the-hacker-playbook-3.md) | 3-4 weeks | Real-world scenarios |

**Lab work:** Complete HackTheBox or TryHackMe machines. Practice full pentest workflow.

---

## Phase 4: Programming for Offense (Weeks 27-33)

**Objective:** Build custom tools and automate workflows.

| Step | Book | Time | What You'll Learn |
|------|------|------|-------------------|
| 10 | [Black Hat Python](../notes/black-hat-python.md) | 3-4 weeks | Offensive Python |
| 11 | [Bash Shell Scripting for Pentesters](../notes/bash-shell-scripting-pentesters.md) | 1-2 weeks | Bash automation |

**Lab work:** Write a custom scanner, automate recon, build a simple C2 framework.

---

## Phase 5: Web Security (Weeks 34-44)

**Objective:** Master web application vulnerabilities and bug bounty methodology.

| Step | Book | Time | What You'll Learn |
|------|------|------|-------------------|
| 12 | [The Web Application Hacker's Handbook](../notes/web-application-hackers-handbook.md) | 4-5 weeks | Every web vuln class |
| 13 | [Bug Bounty Bootcamp](../notes/bug-bounty-bootcamp.md) | 2-3 weeks | Modern bounty hunting |
| 14 | [Real-World Bug Hunting](../notes/real-world-bug-hunting.md) | 2-3 weeks | Real disclosed vulnerabilities |

**Lab work:** Set up DVWA, WebGoat, Juice Shop. Start participating in bug bounty programs.

---

## Phase 6: Windows & Active Directory (Weeks 45-50)

**Objective:** Attack enterprise Windows environments and Active Directory.

| Step | Book | Time | What You'll Learn |
|------|------|------|-------------------|
| 15 | [Kali Linux 2: Windows Penetration Testing](../notes/kali-windows-penetration-testing.md) | 2-3 weeks | Windows-specific attacks |
| 16 | [Mastering Kali Linux for Advanced Penetration Testing](../notes/mastering-kali-advanced-pentest.md) | 2-3 weeks | Advanced techniques, post-exploitation |

**Lab work:** Set up an AD lab with Domain Controller and workstations. Practice BloodHound, Mimikatz, Kerberoasting.

---

## Phase 7: Red Team & Evasion (Weeks 51-60)

**Objective:** Conduct full adversary simulation operations.

| Step | Book | Time | What You'll Learn |
|------|------|------|-------------------|
| 17 | [RTFM: Red Team Field Manual](../notes/rtfm-red-team-field-manual.md) | Reference | Quick command lookup during operations |
| 18 | [Red Teaming Handbook (UK MoD)](../notes/red-teaming-handbook.md) | 1-2 weeks | Strategic red team methodology |
| 19 | [Practical Anti-virus Evasion](../notes/practical-antivirus-evasion.md) | 2-3 weeks | AV bypass, payload crafting |
| 20 | [Cloud Penetration Testing for Red Teamers](../notes/cloud-pentest-red-teamers.md) | 2-3 weeks | Cloud attack techniques |

**Lab work:** Build a C2 infrastructure. Practice AV evasion. Attack cloud lab environments.

---

## Phase 8: Advanced Specialization (Ongoing)

**Objective:** Deep expertise in exploit development and emerging techniques.

| Step | Book | Time | What You'll Learn |
|------|------|------|-------------------|
| 21 | [The Shellcoder's Handbook](../notes/shellcoders-handbook.md) | 4-6 weeks | Binary exploitation, shellcode |
| 22 | [Advanced Penetration Testing — Allsopp](../notes/advanced-penetration-testing-allsopp.md) | 2-3 weeks | Complex, multi-vector attacks |
| 23 | [Creatively Malicious Prompt Engineering](../notes/creatively-malicious-prompt-engineering.md) | 1-2 weeks | AI/LLM attack techniques |

---

## Certification Milestones

| After Phase | Consider |
|-------------|----------|
| Phase 3 | **CEH** — You'll have the knowledge to pass |
| Phase 5 | **eWPT** — Web application testing certification |
| Phase 6 | **OSCP** — The most respected pentesting certification |
| Phase 7 | **CRTO** — Certified Red Team Operator |
| Phase 8 | **OSCE / OSED** — Advanced exploit development |
