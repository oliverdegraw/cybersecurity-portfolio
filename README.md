# 🛡️ Oliver Degraw — Security Architecture Portfolio

**TS/SCI Cleared | CISSP | M.S. Cybersecurity | USAF Cybersecurity Craftsman & Installation ISSM**

📍 Tucson, AZ · 📧 oliverdegraw@gmail.com · 🔗 [LinkedIn](https://www.linkedin.com/in/oliver-degraw-387312137/)

---

## About

I design, authorize, and defend security programs. For 5+ years as a U.S. Air Force Cybersecurity Craftsman and Installation ISSM, that has meant translating DoD, NIST, and DISA requirements into system-specific control architectures — directing RMF/ATO lifecycles, conducting architectural security reviews of every proposed system and network change, and advising leadership on security-by-design.

Separating January 2027. This repository documents the work: architecture artifacts, threat models, investigations, and the technical depth an architect has to design for.

**Trajectory:** Security Engineer / Senior GRC Analyst → **Security Architect**

---

## 🏗️ Architecture

### Zero Trust Architecture — Logical Reference Design
**Status: ✅ Complete** · Graduate capstone, M.S. Cybersecurity (July 2026)

Target-state Zero Trust reference architecture and phased adoption roadmap for a mid-sized enterprise. Maps policy decision and enforcement components to **NIST SP 800-207** (PE / PA / PEP) and structures the design across all five **CISA ZTMM v2.0** pillars — Identity, Devices, Networks, Applications & Workloads, Data — plus Visibility & Analytics, Automation & Orchestration, and Governance.

Addresses a documented phishing-to-lateral-movement scenario by replacing implicit perimeter trust with continuous, identity-centric verification: phishing-resistant MFA and conditional access, device posture at time of access, network microsegmentation, application-layer access brokering, and data classification with policy-based protection.

Delivered as a maturity-driven, phased roadmap rather than an all-or-nothing rebuild — allowing leadership to prioritize investment against risk while maintaining operations.

`NIST SP 800-207` · `CISA ZTMM v2.0` · `OMB M-22-09`

---

### Cloud Security Reference Architecture
**Status: 🔄 In progress**

An AWS reference architecture built to demonstrate identity-centric access control, network segmentation, data protection, and security telemetry — then threat-modeled against its own design.

Scoped deliberately small: every component must justify its presence by mapping to a control objective. Design principles carried forward from the Zero Trust work — no implicit trust, least privilege by default, no long-lived credentials, everything logged, assume breach.

**Deliverables:** scope document · logical architecture diagram · control mapping (implemented control → NIST SP 800-53 → ZTMM pillar) · STRIDE threat model with MITRE ATT&CK (Cloud/IaaS) mapping · design decisions and residual risk writeup

`AWS` · `NIST SP 800-53` · `AWS Well-Architected: Security Pillar` · `STRIDE` · `MITRE ATT&CK`

---

## 🔍 Investigations

### IR-001 — Unauthorized Bluetooth Device, Enterprise Workstation
**Status: ✅ Closed** · Real enterprise forensic investigation

Conducted as ISSO on a classified enterprise network. Windows registry analysis (`BTHPORT`, `bthserv`), event log examination (Event IDs 4624, 4672, 440), FILETIME timestamp conversion, and multi-source artifact corroboration to establish root cause.

**The architecture finding:** the investigation surfaced that the sole Bluetooth-disable control was a manual BIOS step with no GPO enforcement — a systemic control gap across the entire workstation population, not a single-host incident. Escalated with tiered remediation recommendations adopted at installation level.

**MITRE ATT&CK:** `T1200` Hardware Additions · `T1052` Exfiltration Over Physical Medium · `T1562.001` Impair Defenses

📄 [`investigations/IR-001/`](investigations/IR-001/)

> *One missed manual step revealed a missing enforcement layer enterprise-wide. Moving from the single event to the systemic fix is the reflex this portfolio is built around.*

---

## 🔬 Labs & Ongoing Work

| Focus | Detail | Status |
|---|---|---|
| **AWS cloud security lab** | Deployed environment feeding the reference architecture above | 🔄 Active |
| **HackTheBox — SOC Analyst path** | SIEM (Elastic/KQL), threat hunting, Windows internals, detection | 🔄 4/15 |
| **AI-integrated security workflows** | Claude and Codex applied to log triage, ATT&CK mapping, detection development | 🔄 Ongoing |

---

## 📜 Credentials

**Active:** CISSP · CASP+ · CySA+ · PenTest+ · SSCP · Security+ · Network+ · A+ · ITIL 4

**Education:** M.S. Cybersecurity & Information Assurance, WGU (July 2026) · B.S. Cybersecurity & Information Assurance, WGU (March 2025)

**In progress:** CISM · AWS Certified Security – Specialty

**Roadmap:** CCSP → AWS Solutions Architect – Associate → CSA CCZT → SANS GDSA + GMON (GI Bill) → CISSP-ISSAP (2027)

---

## Military Experience → Architecture

| The work | The architecture equivalent |
|---|---|
| RMF control selection & implementation design | Translating requirements into control architectures |
| Security impact analysis on all system/network changes | Architectural security review |
| Advising commanders on security for new systems and construction | Security-by-design advisory |
| Access Control Plan authorship + PKI/MFA/privileged access | IAM policy architecture |
| Boundary protection, segmentation, device compliance | Zero Trust pillar implementation |
| TEMPEST assessment & facility accreditation | Emissions security architecture |
| Complete ATO documentation suite | Enterprise security program design |

---

📧 oliverdegraw@gmail.com · 🔗 [LinkedIn](https://www.linkedin.com/in/oliver-degraw-387312137/)

*Actively maintained.*
