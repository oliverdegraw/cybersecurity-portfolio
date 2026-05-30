# 🛡️ Oliver Degraw — Cybersecurity Portfolio

**TS/SCI Cleared | CISSP | USAF 1D775 Cybersecurity Craftsman → Civilian IR Professional**

📍 Tucson, AZ | 📧 oliverdegraw@gmail.com | 🔗 [LinkedIn](https://www.linkedin.com/in/oliver-degraw-387312137/) | 📓 [Full Portfolio (Notion)](https://www.notion.so/Cybersecurity-Portfolio-5db1ee66bfd3481bbb33fa97cbbbb19d)

---

## About This Repository

I'm a U.S. Air Force Staff Sergeant (E-5) and 7-level 1D775 Cybersecurity Craftsman separating in January 2027 after 5+ years of hands-on cybersecurity work in classified DoD environments. This repository documents my transition from military cyber operations into civilian incident response — tracking investigations, automation scripts, labs, and technical writeups as I build toward a senior IR analyst role in the commercial sector.

Everything here is work-in-progress and actively updated. The goal isn't a polished showcase — it's an honest record of skills being built and applied in real time.

---

## What I'm Building Toward

**Target Role:** Cybersecurity Analyst / Incident Responder (Enterprise/Cloud IR)  
**Target Timeline:** Civilian role by Q1 2027  
**Key Focus Areas:** Incident response, threat hunting, cloud IR (AWS/Azure), digital forensics, security automation, AI-integrated workflows

---

## Current Progress

### 🎓 Education
| Program | Institution | Status |
|---|---|---|
| M.S. Cybersecurity & Information Assurance | Western Governors University | Starting June 2026 |
| B.S. Cybersecurity & Information Assurance | Western Governors University | Completed March 2025 |

### 📜 Certifications
| Certification | Status |
|---|---|
| CISSP | ✅ Active |
| CASP+ | ✅ Active |
| CySA+ | ✅ Active |
| PenTest+ | ✅ Active |
| SSCP / Security+ / Network+ / A+ / ITIL 4 | ✅ Active |
| AWS Certified Security – Specialty | 🔄 In Progress |
| Microsoft AZ-500 | 🔜 Planned |
| GCFA + GCIH + GEIR + GCFE (SANS IR Certificate) | 🔜 GI Bill post-separation |

### 🔬 Hands-On Labs & Training
| Platform | Path / Project | Status |
|---|---|---|
| HackTheBox Academy | SOC Analyst Job Role Path | 🔄 3/15 modules complete |
| HackTheBox | Sherlocks (DFIR Investigations) | 🔜 Starting soon |
| AWS Free Tier | Cloud IR Lab (GuardDuty, CloudTrail, IAM) | 🔜 In Progress |

---

## 🔍 Investigations

### IR-001 — Unauthorized Bluetooth Device | Enterprise Workstation Forensic Investigation
**Date:** May 2026 | **Status:** ✅ Closed

Real enterprise forensic investigation conducted as ISSO. Registry analysis confirmed unauthorized Bluetooth device pairing, Domain Controller coordination identified responsible user, systemic GPO security control gap identified across workstation population.

**Tools:** Windows Registry Editor, PowerShell (Get-PnpDevice, FILETIME conversion), Windows Event Viewer (Event IDs 4624, 4672, 440), Kernel-PnP logs, setupapi.dev.log

**MITRE ATT&CK:** T1200 (Hardware Additions) | T1052 (Exfiltration Over Physical Medium) | T1562.001 (Impair Defenses)

**Key Finding:** Sole Bluetooth disable control was a manual BIOS step with no GPO enforcement — systemic gap identified and escalated for enterprise remediation across full workstation population.

📄 Full report: [`investigations/IR-001/`](investigations/IR-001/)

---

## 🐍 Scripts

### ad-ir-lockdown.ps1 — Active Directory IR Automation
**Language:** PowerShell | **Status:** ✅ Deployed in live environment

Queries Active Directory for specified user accounts and initiates automated lockdown procedures during active security incidents. Developed and deployed for real enterprise IR workflows to accelerate containment response time.

📁 [`scripts/ad-ir-lockdown.ps1`](scripts/)

### ioc-enricher.py — IOC Enrichment Tool *(in development)*
**Language:** Python | Queries VirusTotal API to enrich IPs, hashes, and domains from log files

### cloudtrail-parser.py — CloudTrail Log Analyzer *(in development)*
**Language:** Python | Parses AWS CloudTrail JSON logs and flags suspicious API call patterns

*Scripts added as built. No placeholder code — only working tools.*

---

## 🏠 Home Lab

### AWS Cloud IR Lab *(in progress)*
- **Tools:** GuardDuty, CloudTrail, S3, IAM
- **Objective:** Deploy cloud monitoring environment, introduce intentional misconfigurations, detect and respond, document as formal IR writeup
- **Status:** Account provisioned, building in parallel with AWS Security Specialty cert prep

---

## Military Experience → Civilian Translation

5+ years of DoD cyber operations that directly map to enterprise IR:

| Military Work | Civilian Equivalent |
|---|---|
| ISSO/ISSM — security authorization lifecycle | Security compliance, control implementation, continuous monitoring |
| Incident response for security events on enterprise networks | Enterprise IR — detection, triage, containment, eradication, recovery |
| Registry forensics, event log analysis, artifact collection | Digital forensics and evidence handling |
| Vulnerability assessments on classified systems | Vulnerability management and attack surface analysis |
| PowerShell automation for IR workflows | Security orchestration and automation |
| 24/7 network operations under adversarial conditions | High-stakes IR under time-critical, real-world conditions |
| Forward deployment at Al Udeid AB during active conflict | Mission-critical security under operational pressure |

---

## Contact

📧 oliverdegraw@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/oliver-degraw-387312137/)  
📓 [Notion Portfolio](https://www.notion.so/Cybersecurity-Portfolio-5db1ee66bfd3481bbb33fa97cbbbb19d)

---

*Actively updated as I build. Last updated: May 2026*
