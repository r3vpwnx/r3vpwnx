# Dilanka Kaushal Hewage (`r3vpwnx`)

Independent security researcher. I work on vulnerability research, exploit
development, and coordinated disclosure - auditing real, maintained software,
building working proofs of concept, and reporting what I find to vendors and CVE
authorities.

- Website: https://r3vpwnx.space
- Contact: dilankakaushalhewage@gmail.com

## Research

Independent vulnerability research across open-source and commercial software:
author of 32 published CVEs, spanning OS command injection and memory-safety
bugs in desktop applications and native libraries. I work the full cycle from
source audit to a working proof of concept to coordinated disclosure.

Areas of interest: web applications and services, native code and desktop
applications, Active Directory, and AI/LLM security (autonomous agents, MCP tool
integrations, and RAG pipelines). Advisories are published at https://r3vpwnx.space
as disclosure windows close.

## Exploit development

Proof-of-concept exploits for publicly disclosed CVEs, each written up with a
root-cause analysis and a reproducible PoC. These are exploit implementations for
known vulnerabilities, not original discoveries.

| CVE | Target | Vulnerability class |
|-----|--------|---------------------|
| CVE-2026-26119 | Windows Admin Center | Improper authentication / privilege escalation to PowerShell execution |
| CVE-2025-58434 | Flowise | Unauthenticated account takeover (password-reset token disclosure) |
| CVE-2025-57819 | FreePBX Endpoint Manager | Unauthenticated SQL injection to RCE |
| CVE-2025-55182 | React / Next.js (React2Shell) | RSC Flight deserialization RCE |
| CVE-2025-24367 | Cacti | Authenticated graph-template RCE |
| CVE-2025-8110 | Gogs | Symlink path-traversal arbitrary file write |
| CVE-2007-2447 | Samba | "username map script" command injection |

## Tooling

- [snmpcheck](https://github.com/r3vpwnx/snmpcheck) - SNMP enumeration (Perl, `Net::SNMP`)
- [vpn-manager](https://github.com/r3vpwnx/vpn-manager) - OpenVPN manager for lab and CTF use
- [xl2usernames](https://github.com/r3vpwnx/xl2usernames) - username-list generation for assessments
- [pbkdf2-hashcat-converter](https://github.com/r3vpwnx/pbkdf2-hashcat-converter) - PBKDF2 to Hashcat format
- [RedTeam-ADLab](https://github.com/r3vpwnx/RedTeam-ADLab) - automated Active Directory lab deployment

## Certifications

CRTL, CRTE, CRTP, OSCP+, eCPTX, eCPPT, eWPT, eCRE, eJPT, CRTA

---

All code and write-ups here are for authorized security testing and education only.
