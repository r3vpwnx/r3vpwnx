# Dilanka Kaushal Hewage (`r3vpwnx`)

Red team operator working on adversary emulation, exploit development, and
offensive security research. I build and prove end-to-end exploits against real,
maintained software, then report what I find under coordinated disclosure.

- Website: https://r3vpwnx.space
- Contact: dilankakaushalhewage@gmail.com

## Focus

- Red team operations and adversary emulation
- Vulnerability research and exploit development (web applications, services, and native code)
- Windows internals, kernel exploitation, and driver security (BYOVD)
- Active Directory attack and defense

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

## Research

Ongoing coordinated-disclosure vulnerability research against maintained
open-source and vendor software. Advisories are published here as disclosure
windows close; see https://r3vpwnx.space for write-ups.

## Tooling

- [snmpcheck](https://github.com/r3vpwnx/snmpcheck) - SNMP enumeration (Perl, `Net::SNMP`)
- [vpn-manager](https://github.com/r3vpwnx/vpn-manager) - OpenVPN manager for lab and CTF use
- [xl2usernames](https://github.com/r3vpwnx/xl2usernames) - username-list generation for assessments
- [pbkdf2-hashcat-converter](https://github.com/r3vpwnx/pbkdf2-hashcat-converter) - PBKDF2 to Hashcat format
- [RedTeam-ADLab](https://github.com/r3vpwnx/RedTeam-ADLab) - automated Active Directory lab deployment

## Certifications

CRTL, CRTO, CRTP, CRTE, OSCP+, CPTS, CAPE, CRTA

---

All code and write-ups here are for authorized security testing and education only.
