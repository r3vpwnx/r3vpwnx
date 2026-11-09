# Dilanka Kaushal Hewage (`r3vpwnx`)

Senior Red Team Operator and security researcher. I work on vulnerability
research, exploit development, and coordinated disclosure - auditing real,
maintained software, building working proofs of concept, and reporting what I
find to vendors and CVE authorities.

- Website: https://r3vpwnx.space
- Contact: dilankakaushalhewage@gmail.com

## Research

Independent vulnerability research across open-source and commercial software:
author of 32 published CVEs, spanning unsafe deserialization, code and
expression-language injection, OS command injection, path traversal, and
memory-safety bugs in scientific libraries, desktop applications, and native
code. I work the full cycle from source audit to a working proof of concept to
coordinated disclosure.

Areas of interest: web applications and services, native code and desktop
applications, Active Directory, and AI/LLM security (autonomous agents, MCP tool
integrations, and RAG pipelines). Advisories are published at https://r3vpwnx.space
as disclosure windows close.

### Recent CVEs and advisories

| ID | Target | Class |
|-----|--------|---------------------|
| CVE-2026-120859 | PyMoDAQ | Deserialization of untrusted data and eval injection to RCE (CWE-502 / CWE-94) |
| CVE-2026-120833 | labbench | Pickle deserialization to RCE on a read (CWE-502) |
| CVE-2026-120499 | h5io (and MNE-Python) | Code injection via a crafted HDF5 file (CWE-94) |
| CVE-2026-123095 | mpv | ytdl_hook playlist injection via crafted URLs (CWE-94) |
| CVE-2026-120252 | imagecodecs | Lossless-JPEG (jpegsof3) stack buffer overflow (CWE-121 / CWE-190) |
| CVE-2026-120251 | imagecodecs | CCITT Group-4 (ccittfax4) infinite-loop denial of service (CWE-835) |
| GHSA-ppf5-4gw2-37j9 | GSAS-II | Pickle deserialization to RCE on opening a project file (CWE-502) |

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
