# 05 — Web Security

Web application hacking, bug bounty hunting, API security, and browser exploitation.

Web security is one of the largest and most accessible attack surfaces. This category contains the most books in the collection — reflecting both the breadth of the topic and the demand for web security skills in bug bounty programs and pentesting engagements.

---

## Recommended Study Order

### Foundation Track
1. **Bug Bounty Bootcamp** — Modern, practical introduction to finding web vulnerabilities.
2. **Real-World Bug Hunting** — Learn from actual disclosed bugs with clear explanations.
3. **The Web Application Hacker's Handbook** — The definitive deep-dive reference.

### Bug Bounty Specialization
4. **Bug Bounty Playbook (Ghostlulz)** — Practical methodology for bounty programs.
5. **Bug Bounty Playbook V2** — Advanced techniques.
6. **API Security Threats** — Growing attack surface.

### Advanced Track
7. **JavaScript for Hackers** — Understand client-side attacks at the language level.
8. **The Browser Hacker's Handbook** — Browser exploitation with BeEF.
9. **Advance XSS** — Specialized XSS bypass techniques.

---

## Books in This Category

### Essential

#### The Web Application Hacker's Handbook, 2nd Edition
- **Author:** Dafydd Stuttard, Marcus Pinto
- **Level:** Intermediate
- **Priority:** ⭐⭐⭐⭐⭐
- **Key Topics:** Web app architecture, authentication, session management, access controls, SQL injection, XSS, CSRF, logic flaws, input validation, Burp Suite
- **Why It Matters:** Widely considered the best web security book ever written. Covers every major vulnerability class in depth. Written by the creator of Burp Suite.
- **[Study Notes](../notes/web-application-hackers-handbook.md)**

#### Real-World Bug Hunting
- **Author:** Peter Yaworski
- **Level:** Beginner
- **Priority:** ⭐⭐⭐⭐⭐
- **Key Topics:** SSRF, XXE, IDOR, race conditions, open redirects, subdomain takeover — all from real disclosed reports
- **[Study Notes](../notes/real-world-bug-hunting.md)**

#### Bug Bounty Bootcamp
- **Level:** Beginner
- **Priority:** ⭐⭐⭐⭐⭐
- **Key Topics:** Bug bounty methodology, recon, common vulnerability classes, automation, report writing
- **[Study Notes](../notes/bug-bounty-bootcamp.md)**

### Highly Recommended

| Book | Author | Level | Priority | Focus |
|------|--------|-------|----------|-------|
| [The Browser Hacker's Handbook](../notes/browser-hackers-handbook.md) | Alcorn, Frichot, Orru | Advanced | ⭐⭐⭐⭐ | BeEF, browser hooks, XSS to RCE |
| [JavaScript for Hackers](../notes/javascript-for-hackers.md) | Gareth Heyes | Advanced | ⭐⭐⭐⭐ | JS engine quirks, filter bypass |
| [Bug Bounty Playbook (Ghostlulz)](../notes/bug-bounty-playbook-ghostlulz.md) | Ghostlulz | Intermediate | ⭐⭐⭐⭐ | Structured bounty workflow |
| [Bug Bounty Playbook V2](../notes/bug-bounty-playbook-v2.md) | Unconfirmed | Intermediate | ⭐⭐⭐⭐ | Advanced bounty techniques |
| [A Bug Hunter's Diary](../notes/bug-hunters-diary.md) | Unconfirmed | Intermediate | ⭐⭐⭐⭐ | Real vuln discovery stories |

### Recommended

| Book | Level | Priority | Focus |
|------|-------|----------|-------|
| Becoming the Hacker | Intermediate | ⭐⭐⭐ | Web hacking methodology |
| Bug Bounty Hunting Essentials | Beginner | ⭐⭐⭐ | Bug bounty introduction |
| Bug Bounty Roadmap | Beginner | ⭐⭐⭐ | Learning path for bounty hunters |
| Bug Bounty from Scratch | Beginner | ⭐⭐⭐ | Comprehensive beginner guide |
| Advance XSS | Advanced | ⭐⭐⭐ | XSS bypass techniques |
| API Security Threats | Intermediate | ⭐⭐⭐ | OWASP API Top 10 |
| Awesome Bugbounty Writeups | Intermediate | ⭐⭐⭐ | Curated writeup collection |
| BurpSuite Guide | Beginner | ⭐⭐⭐ | Burp Suite usage |
| CEH v03: Web Applications & Data | Intermediate | ⭐⭐⭐ | EC-Council web module |
| WebPenTestKali | Intermediate | ⭐⭐⭐ | Web pentest with Kali |

---

## Key Tools

- **Burp Suite** — The primary web testing proxy
- **OWASP ZAP** — Free alternative to Burp
- **SQLMap** — Automated SQL injection
- **XSSer** — XSS detection and exploitation
- **DirBuster / ffuf / Gobuster** — Directory/file enumeration
- **Nikto** — Web server scanner
- **Sublist3r / Amass** — Subdomain enumeration
- **Postman / curl** — API testing

---

## Related Categories

- [06 — Pentesting](../06-pentesting/) — Web testing as part of full pentest methodology
- [08 — Programming for Security](../08-programming-for-security/) — Build custom web testing tools
- [09 — Exploit Development](../09-exploit-development/) — When web bugs lead to code execution
