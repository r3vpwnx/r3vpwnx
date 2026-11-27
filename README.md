## Dilanka Kaushal Hewage (r3vpwnx)

Senior Red Team Operator and security researcher focused on vulnerability research, exploit development and coordinated disclosure. I audit real, maintained software, build working proofs of concept, and report findings to maintainers and CVE Numbering Authorities.

[r3vpwnx.space](https://r3vpwnx.space) &nbsp;|&nbsp; [LinkedIn](https://www.linkedin.com/in/r3vpwnx) &nbsp;|&nbsp; [ORCID](https://orcid.org/0009-0009-7191-468X) &nbsp;|&nbsp; dilankakaushalhewage@gmail.com

### Research

Credited with 29 published CVEs and 7 further GitHub security advisories in open-source and commercial software, covering unsafe deserialization, code injection, OS command injection, path traversal and memory-safety bugs in scientific libraries, desktop applications and native code. Advisories are published on [r3vpwnx.space](https://r3vpwnx.space) once disclosure windows close.

Current interests: native and desktop application security, web applications, Active Directory, and AI/LLM security (agents, MCP tool integrations, RAG pipelines).

**Published CVEs and advisories**

| ID | Project | Vulnerability |
| --- | --- | --- |
| [CVE-2026-137999](https://www.cve.org/CVERecord?id=CVE-2026-137999) | JSONSchema2PoPo2 | Code injection via unescaped schema defaults in generated classes |
| [CVE-2026-137998](https://www.cve.org/CVERecord?id=CVE-2026-137998) | Detoxify | Unsafe checkpoint deserialization (torch.load) leading to RCE |
| [CVE-2026-137997](https://www.cve.org/CVERecord?id=CVE-2026-137997) | HCIPy | Pickle deserialization when reading field, grid or mode-basis files |
| [CVE-2026-137996](https://www.cve.org/CVERecord?id=CVE-2026-137996) | Zettlr | Unvalidated URI schemes opened from Markdown links |
| [CVE-2026-137994](https://www.cve.org/CVERecord?id=CVE-2026-137994) | Leo&nbsp;Editor | Pickle deserialization when opening a .leo outline leading to RCE |
| [CVE-2026-137539](https://www.cve.org/CVERecord?id=CVE-2026-137539) | lastversion | Arbitrary file write via tar symlink members on extract |
| [CVE-2026-137529](https://www.cve.org/CVERecord?id=CVE-2026-137529) | JAL&nbsp;(Just&nbsp;Another&nbsp;Ledger) | Arbitrary file overwrite via a symlink in a backup archive |
| [CVE-2026-137518](https://www.cve.org/CVERecord?id=CVE-2026-137518) | pyfda | Pickle deserialization when loading a filter file leading to RCE |
| [CVE-2026-137506](https://www.cve.org/CVERecord?id=CVE-2026-137506) | ezdxf | Code injection in dxf2code via DXF table entry names |
| [CVE-2026-136923](https://www.cve.org/CVERecord?id=CVE-2026-136923) | asar-py | Path traversal on archive extraction (arbitrary file write) |
| [CVE-2026-136922](https://www.cve.org/CVERecord?id=CVE-2026-136922) | PyBioNetGen | Code execution via sympify of BNG-XML parameter expressions |
| [CVE-2026-136168](https://www.cve.org/CVERecord?id=CVE-2026-136168) | RedVector | Command allow-list bypass and hard-coded API token leading to RCE |
| [CVE-2026-136167](https://www.cve.org/CVERecord?id=CVE-2026-136167) | vedo | Pickle deserialization when opening .npy/.npz files leading to RCE |
| [CVE-2026-134704](https://www.cve.org/CVERecord?id=CVE-2026-134704) | OpenShot | Pickle deserialization when opening a project file (.osp) leading to RCE |
| [CVE-2026-134694](https://www.cve.org/CVERecord?id=CVE-2026-134694) | gammapy | Eval injection via the WCSSHAPE FITS header leading to RCE |
| [CVE-2026-103926](https://www.cve.org/CVERecord?id=CVE-2026-103926) | hickle | safe=True load flag ignored, pickle deserialization leading to RCE |
| [GHSA-632c-gw75-99r3](https://github.com/hyperspy/hyperspy/security/advisories/GHSA-632c-gw75-99r3) | HyperSpy | Code execution via file-derived SymPy expressions on load |
| [GHSA-j975-x368-3hrr](https://github.com/hyperspy/hyperspy/security/advisories/GHSA-j975-x368-3hrr) | HyperSpy | cloudpickle deserialization when restoring a stored model |
| [CVE-2026-133708](https://www.cve.org/CVERecord?id=CVE-2026-133708) | diffpy.structure | Eval injection via CIF symmetry operations leading to RCE |
| [CVE-2026-133707](https://www.cve.org/CVERecord?id=CVE-2026-133707) | targets&nbsp;(R) | Code injection via a shared pipeline store leading to RCE |
| [CVE-2026-132751](https://www.cve.org/CVERecord?id=CVE-2026-132751) | yt | Eval injection via a ytdata HDF5 file (con_args) leading to RCE |
| [CVE-2026-129855](https://www.cve.org/CVERecord?id=CVE-2026-129855) | RedAmon | Unauthenticated root shell over a WebSocket (port 8016) |
| [CVE-2026-129854](https://www.cve.org/CVERecord?id=CVE-2026-129854) | RedAmon | Cross-tenant control of live post-exploitation sessions (BOLA) |
| [CVE-2026-118692](https://www.cve.org/CVERecord?id=CVE-2026-118692) | CherryTree | OS command injection via the weblink action (independent co-discovery) |
| [CVE-2026-120859](https://www.cve.org/CVERecord?id=CVE-2026-120859) | PyMoDAQ | Unsafe deserialization and eval injection leading to RCE |
| [CVE-2026-120499](https://www.cve.org/CVERecord?id=CVE-2026-120499) | h5io&nbsp;/&nbsp;MNE-Python | Code injection via crafted HDF5 file (eval, import, unpickle) |
| [CVE-2026-120833](https://www.cve.org/CVERecord?id=CVE-2026-120833) | labbench&nbsp;(NIST) | Pickle deserialization leading to RCE |
| [GHSA-ppf5-4gw2-37j9](https://github.com/AdvancedPhotonSource/GSAS-II/security/advisories/GHSA-ppf5-4gw2-37j9) | GSAS-II&nbsp;(DOE&nbsp;/&nbsp;Argonne) | Pickle deserialization leading to RCE on project open |
| [CVE-2026-126042](https://www.cve.org/CVERecord?id=CVE-2026-126042) | VNote | OS command injection via Tasks magic variables |
| [CVE-2026-123095](https://www.cve.org/CVERecord?id=CVE-2026-123095) | mpv | Playlist injection in ytdl_hook (CRLF) |
| [CVE-2026-120252](https://www.cve.org/CVERecord?id=CVE-2026-120252) | imagecodecs | Stack buffer overflow in lossless JPEG decoder |
| [CVE-2026-120251](https://www.cve.org/CVERecord?id=CVE-2026-120251) | imagecodecs | Infinite loop in CCITT Group 4 decoder |
| [GHSA-9r9x-g862-525c](https://github.com/HHS/Head-Start-TTADP/security/advisories/GHSA-9r9x-g862-525c) | Head&nbsp;Start&nbsp;TTADP&nbsp;(US&nbsp;HHS) | Cross-region write IDOR (broken access control) |
| [GHSA-q859-79hf-rpr3](https://github.com/HHS/Head-Start-TTADP/security/advisories/GHSA-q859-79hf-rpr3) | Head&nbsp;Start&nbsp;TTADP&nbsp;(US&nbsp;HHS) | Cross-region read IDOR on the communication-log endpoint |
| [GHSA-fmqx-8x8h-gf76](https://github.com/pbek/QOwnNotes/security/advisories/GHSA-fmqx-8x8h-gf76) | QOwnNotes | Path traversal in note media/attachment handling |
| [GHSA-jp2h-69pm-p69c](https://github.com/pbek/QOwnNotes/security/advisories/GHSA-jp2h-69pm-p69c) | QOwnNotes | Command injection via note filenames in the external Git version viewer |

### Exploit development

Proof-of-concept exploits with root-cause analysis for publicly disclosed vulnerabilities. These CVEs were discovered by other researchers.

| CVE | Target | Vulnerability |
| --- | --- | --- |
| CVE-2026-120752 | PyMuPDF | Stack buffer overflow in callout annotation (credited analyst) |
| CVE-2026-26119 | Windows&nbsp;Admin&nbsp;Center | Improper authentication to PowerShell execution |
| CVE-2025-58434 | Flowise | Unauthenticated account takeover |
| CVE-2025-57819 | FreePBX&nbsp;Endpoint&nbsp;Manager | Unauthenticated SQL injection to RCE |
| CVE-2025-55182 | React&nbsp;/&nbsp;Next.js | RSC Flight deserialization RCE |
| CVE-2025-24367 | Cacti | Authenticated graph-template RCE |
| CVE-2025-8110 | Gogs | Symlink path traversal to arbitrary file write |
| CVE-2007-2447 | Samba | username map script command injection |

### Tools

- **RedTeam-ADLab**: automated Active Directory lab deployment
- **snmpcheck**: SNMP enumeration
- **xl2usernames**: username-list generation for assessments
- **pbkdf2-hashcat-converter**: PBKDF2 to Hashcat format conversion
- **vpn-manager**: OpenVPN manager for lab environments

### Certifications

OSCP+ · CRTL · CRTE · CRTP · CRTA · eCPTX · eCPPT · eWPT · eCRE · eJPT

---

<sub>All code and write-ups are provided for authorized security testing and education only.</sub>
