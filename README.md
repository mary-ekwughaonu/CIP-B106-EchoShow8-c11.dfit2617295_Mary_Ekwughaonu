# CIP-B106-EchoShow8-c11.dfit2617295_Mary_Ekwughaonu
Echo Show 8 IoT Forensics Case Study – CIP B106
# CIP-B106 Echo Show 8 IoT Forensics Case Study

**Student:** Mary Ekwughaonu  
**Registration Number:** c11.dfit2617295  
**Case Identifier:** CIPB106-EchoShow8-c11.dfit2617295  
**Course:** CIP B106 – Mobile and IoT Forensics  
**Submission Date:** 17 October 2026

---

## Case Overview

Forensic examination of an Amazon Echo Show 8 training eMMC image.  
The investigation covered device identification, user/account evidence, network configuration, phone communication artefacts, multimedia evidence, and timeline reconstruction.

### Key Findings

- **Device:** Amazon Echo Show 8 (Model AEOAT, Codename athena)
- **OS:** Android 9 (Build PS7560.3677N, Security Patch 2022-01-01)
- **Account:** “Sarfraz” (com.amazon.account) + multiple Amazon sync accounts
- **User Role:** ADULT / REGISTERED
- **Wi-Fi Networks:** Fios-pJK9q and TellMyWiFiLoveHer
- **Media Counts (account level):** 29 photos, 2 videos
- **Phone / Call content:** Limited (no recoverable call records)
- **Local user media:** Limited (mostly system assets)

---

## Folder Structure
CIP-B106-EchoShow8-c11.dfit2617295_Mary_Ekwughaonu/
├── Original/               # Original evidence (Echo_Device.zip)
├── Working/                # Working copies, extracted images, reports
│   └── reports/            # Task A–E summary reports
├── Hashes/                 # MD5 and SHA-256 of original evidence
├── Findings/               # Individual finding files (F-01 to F-36)
├── Notes/                  # Activity log
NOTE THE EVIDENCE FILE WAS NOT INCLUDED

---

## Evidence Integrity

| Algorithm | Hash Value |
|-----------|------------|
| **MD5** | `9b2bfdd21add65d0ffb77908ade7915a` |
| **SHA-256** | `6051faa0888c64e2450a58182ec647c223eedf776362cbc8d660bf1cdaae701c` |

---

## Tools Used

- Kali Linux
- 7z, mmls, dd, mount (read-only)
- sqlite3, find, grep, strings, file
- Manual Base64 decoding and cross-source validation

---

## Tasks Completed

| Task | Description | Status |
|------|-------------|--------|
| Task A | Device Profile, Accounts, Wi-Fi | Completed |
| Task B | User Settings & Internal Storage | Completed |
| Task C | Network Connectivity | Completed |
| Task D | Phone Communication | Completed |
| Task E | Multimedia Evidence | Completed |
| Task F | Timeline & Final Findings | Completed |

---

## Final Report

Main deliverable:  
`CIP-B106_CaseStudy3_c11.dfit2617295_Mary_Ekwughaonu_EchoShow8.docx` / `.pdf`

---

## Academic Integrity

This work reflects the student’s own examination of the authorised course evidence.  
All sources, tools, and assistance have been identified.

---

**End of README**
EOF

echo "README.md created successfully"
ls -l README.md
