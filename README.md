
# NIGHT PULSE X — Arsenal

**The Ultimate Red Team Knowledge Base**

A comprehensive, research-driven offensive security encyclopedia designed for penetration testing, CTF competitions, red team operations, and defensive validation. This living knowledge base consolidates techniques, methodologies, tools, and vulnerabilities from across the security community into a single structured reference.

---

## 🔍 Overview

**Arsenal** is a purpose-built knowledge base that transforms scattered security research into an actionable, structured reference. It follows a repeatable assessment model:

```
Scope → Reconnaissance → Enumeration → Hypothesis → Validation → Evidence → Remediation → Retest
```

Whether you're preparing for an OSCP exam, hunting for bug bounties, or conducting an authorized red team engagement, Arsenal provides the foundational knowledge and practical commands you need.

---

## 📚 What's Inside

### 1. **Complete Tool Arsenal (2025–2026)**
- Core pentesting tools: Nmap, Metasploit, Burp Suite, SQLmap, John/Hashcat, BloodHound, Impacket, Ligolo-ng, Mimikatz
- New additions from Kali Linux 2026.1: AdaptixC2, SSTImap, WPProbe, XSStrike
- AI-powered pentesting tools: PentAGI, RapidPen, Snyk Evo, Specter, T3MP3ST

### 2. **Reconnaissance & OSINT**
- Passive/active recon methodologies
- Subdomain enumeration, DNS mapping, certificate transparency
- Cloud OSINT (AWS/Azure/GCP asset discovery)
- Technology fingerprinting, JS reconnaissance, attack-surface mapping

### 3. **Enumeration & Service Discovery**
- HTTP/HTTPS, DNS, SMB, LDAP, Kerberos, SSH, SNMP, RDP, WinRM
- Database enumeration (MySQL, MSSQL, PostgreSQL, Redis)
- Container and Kubernetes surface mapping
- API route discovery, GraphQL introspection, WebSocket inventory

### 4. **Web Application & API Security**
- SQL/NoSQL injection, XSS, SSTI, Command Injection
- SSRF, XXE, Deserialization, Prototype Pollution
- GraphQL security, WebSocket authorization, JWT validation
- OAuth/OIDC, session management, IDOR/BOLA, BFLA
- Business logic flaws, race conditions, cache poisoning/deception
- HTTP/2/3, request smuggling, parser differentials

### 5. **Active Directory & Entra ID**
- BloodHound with advanced Cypher queries
- Kerberos attacks: Kerberoasting, AS-REP Roasting, Pass-the-Ticket, Golden/Silver Tickets
- DCSync, RBCD, Shadow Credentials, AD CS (ESC1-ESC8)
- GPO analysis, delegation abuse, LAPS, DPAPI
- Lateral movement: Pass-the-Hash, WMI, PSExec, WinRM, DCOM

### 6. **Linux Privilege Escalation**
- SUID/SGID abuse, Sudo exploitation, capability abuse
- Kernel exploits (CVE-2025-40271, CVE-2026-43284, and more)
- Cron jobs, writable files, LD_PRELOAD hijacking
- Docker/LXC escape techniques
- Automated enumeration (LinPEAS, pspy)

### 7. **Windows Privilege Escalation**
- UAC bypass, SeImpersonate/SeBackup/SeRestore abuse
- Potato attacks (JuicyPotato, PrintSpoofer, GodPotato)
- Unquoted service paths, writable service binaries
- AlwaysInstallElevated, stored credentials
- Automated enumeration (WinPEAS, PowerUp, Seatbelt)

### 8. **Binary Exploitation & Vulnerability Research**
- ROP chain construction, ret2libc, ret2syscall
- Heap exploitation: TCache poisoning, UAF, House of X
- Format string attacks, canary bypass
- Fuzzing strategies, patch diffing, CVE research
- ASLR, DEP/NX, stack protections, CFI

### 9. **Container & Kubernetes Security**
- Docker escape (privileged containers, socket exposure)
- runc vulnerabilities (CVE-2025-31133, CVE-2025-52565, CVE-2025-52881)
- Kubernetes RBAC, service account abuse, admission controls
- Image provenance, registry security, secrets management

### 10. **Cloud Security (AWS/Azure/GCP)**
- IAM privilege escalation, misconfiguration discovery
- Metadata service abuse (IMDSv1/v2)
- S3 bucket enumeration, Azure Storage exposure
- GCP service account impersonation
- Cloud logging, incident readiness

### 11. **AI & LLM Security**
- Prompt injection, indirect prompt injection
- RAG security, vector database protection
- Tool/function calling authorization, agent security
- Model supply chain, data exfiltration through tools
- MCP (Model Context Protocol) security

### 12. **Pivoting & Tunneling**
- Ligolo-ng advanced tunneling
- SSH dynamic proxies, port forwarding
- Chisel SOCKS tunneling, SMB/NTLM relaying
- Proxychains, ADIDNS poisoning

### 13. **AV/EDR Bypass**
- AMSI bypass techniques
- Donut (EXE to shellcode conversion)
- Reflective injection, unmanaged PowerShell
- Process injection, memory-only payloads

### 14. **Post-Exploitation**
- Shell upgrades (TTY, Python, Socat)
- Credential dumping (Mimikatz, secretsdump, LSASS)
- Persistence mechanisms (Linux/Windows)
- Exfiltration techniques (Netcat, DNS, ICMP, HTTP/S)

### 15. **Reporting & Documentation**
- Professional report structure (Executive Summary, Findings, Remediation)
- Reporting tools: APTRS, OWASP VISTO, PlexTrac
- Evidence preservation, severity scoring, retest planning

---

## 🛠️ Key Features

| Feature | Description |
|---------|-------------|
| **Collapsible Sections** | All knowledge modules are toggleable for easy navigation |
| **Advanced Search** | Global search across all techniques, tools, and commands |
| **Multi-language Support** | UI available in 12 languages (English, Arabic, French, etc.) |
| **Interactive Filtering** | Filter content by category (Recon, Web, AD, Cloud, etc.) |
| **Bookmarks** | Save and organize important sections |
| **Command Palette** | Quick jump to any section (Ctrl+K) |
| **Copy-to-Clipboard** | One-click copy for all code blocks and commands |

---

## 📊 Content Statistics

- **250+** Techniques covered
- **150+** Ready-to-use commands
- **12** Attack chains
- **17** Knowledge domains
- **∞** Payload combinations

---

## 🎯 Who Is This For?

| Role | How Arsenal Helps |
|------|-------------------|
| **Penetration Testers** | Quick reference for enumeration, exploitation, and privilege escalation |
| **CTF Players** | Comprehensive command library and methodology guidance |
| **Bug Bounty Hunters** | Web/API testing techniques, IDOR/BOLA methodologies, reporting templates |
| **Red Teamers** | Advanced AD attacks, cloud exploitation, EDR evasion |
| **Blue Teamers** | Detection engineering, threat hunting, telemetry validation |
| **Security Researchers** | Vulnerability research methodologies, CVE tracking, fuzzing strategies |
| **Students & Beginners** | Structured learning path, hands-on commands, certification roadmap |

---

## 🚀 Quick Navigation

### Start Here
- [Assessment Compass](#npx20-overview) – Core methodology and workflow
- [Discovery Tree](#npx25-attack-tree) – Visual attack surface mapping
- [Command Center](#npx26-command-center) – Bug bounty and career path

### Core Domains
- [Reconnaissance](#recon) – Information gathering and OSINT
- [Enumeration](#enum) – Service and application mapping
- [Web Attacks](#v20-web-hub) – Modern web application testing
- [Active Directory](#ad-enum) – Windows domain security
- [Linux PrivEsc](#privesc-linux) – Linux privilege escalation
- [Windows PrivEsc](#privesc-windows) – Windows privilege escalation
- [Binary Exploitation](#binary) – ROP, heap, and vulnerability research

### Reference
- [Ports & Services](#ports) – Common port reference
