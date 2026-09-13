# 13 — Telecom & SS7

SS7 protocol security, mobile network attacks, signaling system exploitation, and telecom infrastructure.

This is a specialized area covering the vulnerabilities in the Signaling System No. 7 (SS7) protocol stack — the backbone of traditional mobile telecommunications. SS7 attacks allow call interception, SMS interception, location tracking, and fraud. This collection has unusually deep coverage of this topic.

---

## Background

SS7 (Signaling System No. 7) is a set of signaling protocols used by telecom operators worldwide. Originally designed in the 1970s-80s with implicit trust between operators, SS7 has significant security vulnerabilities that have been publicly disclosed since the early 2010s. Despite Diameter (used in 4G/LTE), many of these issues persist due to SS7/Diameter interworking.

---

## Recommended Study Order

1. **Signaling System 7 (SS7)** (small reference) — Protocol fundamentals.
2. **Vulnerabilities of SS7 to cyber attacks** (Bob Kamwendo) — Academic overview of SS7 vulnerabilities.
3. **SS7 Security Report** — Comprehensive vulnerability assessment.
4. **SS7: Locate. Track. Manipulate.** (Tobias Engel) — The landmark presentation on SS7 attacks.
5. **Hacking mobile network via SS7** (Dmitry Kurbatov) — Practical exploitation.
6. **Stealthy SS7 Attacks** — Advanced evasion.
7. **SCTPscan** and **Telecommunications Infrastructure** (Philippe Langlois) — Finding and attacking SS7 entry points.

---

## Books in This Category

### Essential

#### SS7: Locate. Track. Manipulate.
- **Author:** Tobias Engel
- **Level:** Expert
- **Priority:** ⭐⭐⭐⭐⭐
- **Key Topics:** SS7 architecture, MAP protocol, location tracking via SS7, call/SMS interception, subscriber information retrieval
- **Why It Matters:** The presentation that brought SS7 security issues to mainstream attention. Tobias Engel's work at 31C3 demonstrated how any party with SS7 access could track mobile phone users globally.
- **[Study Notes](../notes/ss7-locate-track-manipulate.md)**

### Highly Recommended

| Book | Author | Level | Priority |
|------|--------|-------|----------|
| [SS7 Security Report](../notes/ss7-security-report.md) | Unconfirmed | Advanced | ⭐⭐⭐⭐ |
| [Hacking mobile network via SS7](../notes/hacking-mobile-network-ss7.md) | Dmitry Kurbatov | Advanced | ⭐⭐⭐⭐ |

### Recommended

| Book | Author | Level | Priority |
|------|--------|-------|----------|
| Stealthy SS7 Attacks | Sergey Puzankov | Advanced | ⭐⭐⭐ |
| SCTPscan: Finding entry points to SS7 Networks | Philippe Langlois | Expert | ⭐⭐⭐ |
| Telecommunications Infrastructure: SS7 Signalling Security | Philippe Langlois | Advanced | ⭐⭐⭐ |
| Cellular location tracking attacks | Aalto University | Advanced | ⭐⭐⭐ |
| Vulnerabilities of SS7 to cyber attacks | Bob Kamwendo | Intermediate | ⭐⭐⭐ |
| Signaling System 7 (SS7) (small reference) | Unconfirmed | Intermediate | ⭐⭐ |

### Unidentified

| File | Notes |
|------|-------|
| TELECO_2.PDF | Unidentified — likely telecom-related based on filename |
| AD1027344.pdf | Unidentified — possibly military/academic telecom paper based on document ID format |

---

## Key Protocols & Concepts

- **SS7/C7** — Signaling System No. 7 / Common Channel Signalling System No. 7
- **MAP** — Mobile Application Part
- **CAP** — CAMEL Application Part
- **SCTP** — Stream Control Transmission Protocol
- **SIGTRAN** — Signaling Transport (SS7 over IP)
- **Diameter** — 4G/LTE signaling protocol (successor to SS7)
- **HLR/VLR** — Home/Visitor Location Register
- **IMSI** — International Mobile Subscriber Identity

---

## Related Categories

- [02 — Network Security](../02-network-security/) — Network-level concepts underlying telecom
- [10 — Mobile & IoT Hacking](../10-mobile-iot-hacking/) — Mobile device/app perspective
