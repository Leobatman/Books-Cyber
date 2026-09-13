# Web Security Learning Path

A focused path for specializing in web application security and bug bounty hunting.

This path is ideal for aspiring bug bounty hunters, web application pentesters, and developers who want to understand how web applications are attacked.

---

## Prerequisites

- Basic HTML, CSS, and JavaScript knowledge
- Understanding of HTTP protocol (requests, responses, headers, cookies)
- Familiarity with browser developer tools
- Linux command-line basics (see [03 — Linux](../03-linux/))

---

## Phase 1: Web Hacking Foundations (Weeks 1-6)

| Step | Book | Time | What You'll Learn |
|------|------|------|-------------------|
| 1 | [Bug Bounty Bootcamp](../notes/bug-bounty-bootcamp.md) | 2-3 weeks | Bug bounty methodology, common vulns, recon |
| 2 | [Real-World Bug Hunting](../notes/real-world-bug-hunting.md) | 2-3 weeks | Real vulnerability examples from disclosed reports |

**Lab work:** Set up Burp Suite (Community Edition). Practice on DVWA and PortSwigger Web Security Academy.

---

## Phase 2: Deep Web Security (Weeks 7-16)

| Step | Book | Time | What You'll Learn |
|------|------|------|-------------------|
| 3 | [The Web Application Hacker's Handbook](../notes/web-application-hackers-handbook.md) | 5-6 weeks | Complete web security reference |
| 4 | BurpSuite Guide | 1-2 weeks | Mastering your primary testing tool |
| 5 | API Security Threats | 1 week | API-specific vulnerability patterns |

**Lab work:** Work through every PortSwigger lab. Start testing real bug bounty programs (low-hanging fruit).

---

## Phase 3: Bug Bounty Methodology (Weeks 17-24)

| Step | Book | Time | What You'll Learn |
|------|------|------|-------------------|
| 6 | [Bug Bounty Playbook (Ghostlulz)](../notes/bug-bounty-playbook-ghostlulz.md) | 2 weeks | Structured bounty workflow |
| 7 | [Bug Bounty Playbook V2](../notes/bug-bounty-playbook-v2.md) | 2 weeks | Advanced techniques |
| 8 | Bug Bounty from Scratch | 2 weeks | Comprehensive approach |
| 9 | Awesome Bugbounty Writeups | Ongoing | Real writeups for inspiration |

**Lab work:** Active bug bounty participation. Focus on 2-3 programs and go deep.

---

## Phase 4: Advanced Client-Side (Weeks 25-34)

| Step | Book | Time | What You'll Learn |
|------|------|------|-------------------|
| 10 | [JavaScript for Hackers](../notes/javascript-for-hackers.md) | 3 weeks | JS engine internals, filter bypass |
| 11 | Advance XSS | 2 weeks | Advanced XSS bypass techniques |
| 12 | [The Browser Hacker's Handbook](../notes/browser-hackers-handbook.md) | 4 weeks | Browser exploitation with BeEF |

**Lab work:** Build custom XSS payloads. Experiment with BeEF. Hunt for client-side vulnerabilities.

---

## Phase 5: Supporting Skills (Weeks 35-42)

| Step | Book | Time | What You'll Learn |
|------|------|------|-------------------|
| 13 | [Black Hat Python](../notes/black-hat-python.md) | 3 weeks | Build custom web testing tools |
| 14 | [A Bug Hunter's Diary](../notes/bug-hunters-diary.md) | 1-2 weeks | Vulnerability research mindset |
| 15 | WebPenTestKali | 2 weeks | Web pentest methodology with Kali |

---

## Key Skills to Develop

| Skill | Resources |
|-------|-----------|
| **Recon** | Amass, Sublist3r, asset discovery, Google dorking |
| **Proxy Interception** | Burp Suite, mitmproxy |
| **SQL Injection** | SQLMap, manual injection techniques |
| **XSS** | DOM-based, reflected, stored, polyglot payloads |
| **SSRF** | Cloud metadata endpoints, internal service access |
| **Authentication Bypass** | JWT attacks, session fixation, OAuth flaws |
| **API Testing** | Postman, curl, authorization testing |
| **Automation** | Custom Python scripts, nuclei, ffuf |

---

## Certification Milestones

| After Phase | Consider |
|-------------|----------|
| Phase 2 | **eWPT** — eLearnSecurity Web Application Penetration Tester |
| Phase 4 | **BSCP** — Burp Suite Certified Practitioner |
| Phase 5 | **OSWE** — Offensive Security Web Expert |
