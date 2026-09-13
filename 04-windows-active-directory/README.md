# 04 — Windows & Active Directory

Windows exploitation, Active Directory attacks, and domain compromise techniques.

Active Directory is the backbone of enterprise networks. Compromising AD is often the primary objective in penetration tests and red team engagements. This is a critical skill area for anyone pursuing OSCP or professional pentesting.

---

## Recommended Study Order

1. **Kali Linux 2: Windows Penetration Testing** — Windows-specific exploitation from a Kali perspective.
2. **Active Directory Bypass Techniques** — Focused on AD-specific attacks and evasion.

> **Note:** This category has limited dedicated books in the current collection. For more AD content, see also:
> - [The Hacker Playbook 3](../06-pentesting/) — Contains significant AD attack content
> - [RTFM: Red Team Field Manual](../07-red-team/) — Quick AD command reference
> - [Mastering Kali Linux for Advanced Penetration Testing](../06-pentesting/) — Includes post-exploitation and lateral movement

---

## Books in This Category

#### Kali Linux 2: Windows Penetration Testing
- **Level:** Intermediate
- **Priority:** ⭐⭐⭐⭐
- **Key Topics:** Windows exploitation using Kali, SMB attacks, RDP, PowerShell, credential harvesting, lateral movement
- **[Study Notes](../notes/kali-windows-penetration-testing.md)**

#### Active Directory Bypass Techniques (AC DER BY PASS TECH.HACKERS)
- **Level:** Advanced
- **Priority:** ⭐⭐⭐
- **Key Topics:** AD enumeration bypass, credential attacks, Kerberos abuse, evasion techniques
- **Note:** File title suggests Portuguese-language content focused on AD bypass methods.

---

## Key Tools for This Category

- **BloodHound** — AD relationship mapping and attack path analysis
- **Mimikatz** — Credential extraction
- **Rubeus** — Kerberos abuse
- **PowerView** — AD enumeration
- **CrackMapExec** — Network/AD attack automation
- **Impacket** — Python tools for Windows protocol manipulation

---

## Related Categories

- [06 — Pentesting](../06-pentesting/) — General methodology that applies to Windows targets
- [07 — Red Team](../07-red-team/) — Full adversary simulation including AD compromise
- [09 — Exploit Development](../09-exploit-development/) — Windows binary exploitation
