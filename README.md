# 🌙 NIGHT PULSE X — Arsenal

> *The Ultimate Red Team Knowledge Base*

<p align="center">
  <a href="https://npx-official.github.io/projects/arsenal"><img src="https://img.shields.io/badge/🌐-Live_Demo-6fffe0?style=for-the-badge&logo=google-chrome&logoColor=white"/></a>
  <a href="https://github.com/npx-official/Arsenal-Red-Team-Encyclopedia"><img src="https://img.shields.io/badge/🐙-GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/></a>
  <a href="https://github.com/npx-official/Arsenal-Red-Team-Encyclopedia/stargazers"><img src="https://img.shields.io/github/stars/npx-official/Arsenal-Red-Team-Encyclopedia?style=for-the-badge&color=gold"/></a>
  <a href="https://github.com/npx-official/Arsenal-Red-Team-Encyclopedia/forks"><img src="https://img.shields.io/github/forks/npx-official/Arsenal-Red-Team-Encyclopedia?style=for-the-badge&color=6fffe0"/></a>
  <a href="https://github.com/npx-official/Arsenal-Red-Team-Encyclopedia/blob/main/LICENSE"><img src="https://img.shields.io/badge/📜-MIT_License-6fffe0?style=for-the-badge"/></a>
</p>

<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=28&duration=3500&pause=1000&color=6FFFE0&center=true&vCenter=true&width=700&lines=⚡+Arsenal+%7C+Offensive+Security+Encyclopedia;🔍+250%2B+Techniques+%7C+150%2B+Commands;🌍+12+Languages+Supported;🎯+OSCP+%7C+CTF+%7C+Red+Team+Ready" alt="Typing SVG" />
</div>

<br>

---

## 🎯 Overview

**Arsenal** is a comprehensive, research-driven offensive security encyclopedia designed for penetration testing, CTF competitions, red team operations, and defensive validation. It transforms scattered security research into an actionable, structured reference following a repeatable assessment model:

<p align="center">
  <img src="https://img.shields.io/badge/📋-Scope-6fffe0?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/🔍-Recon-a78bfa?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/📡-Enumeration-6fffe0?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/🧠-Hypothesis-a78bfa?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/✅-Validation-6fffe0?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/📸-Evidence-a78bfa?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/🔧-Remediation-6fffe0?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/🔄-Retest-a78bfa?style=for-the-badge"/>
</p>

Whether you're preparing for an OSCP exam, hunting for bug bounties, or conducting an authorized red team engagement, Arsenal provides the foundational knowledge and practical commands you need.

---

## 📚 What's Inside

### 🛠️ Complete Tool Arsenal (2025–2026)
| Category | Tools |
|----------|-------|
| **Core Pentesting** | Nmap, Metasploit, Burp Suite, SQLmap, John/Hashcat, BloodHound, Impacket, Ligolo-ng, Mimikatz |
| **Kali Linux 2026.1** | AdaptixC2, SSTImap, WPProbe, XSStrike |
| **AI-Powered** | PentAGI, RapidPen, Snyk Evo, Specter, T3MP3ST |

### 🔍 Reconnaissance & OSINT
- Passive/active recon methodologies
- Subdomain enumeration, DNS mapping, certificate transparency
- Cloud OSINT (AWS/Azure/GCP asset discovery)
- Technology fingerprinting, JS reconnaissance, attack-surface mapping

### 📡 Enumeration & Service Discovery
- HTTP/HTTPS, DNS, SMB, LDAP, Kerberos, SSH, SNMP, RDP, WinRM
- Database enumeration (MySQL, MSSQL, PostgreSQL, Redis)
- Container and Kubernetes surface mapping
- API route discovery, GraphQL introspection, WebSocket inventory

### 🌐 Web Application & API Security
- SQL/NoSQL injection, XSS, SSTI, Command Injection
- SSRF, XXE, Deserialization, Prototype Pollution
- GraphQL security, WebSocket authorization, JWT validation
- OAuth/OIDC, session management, IDOR/BOLA, BFLA
- Business logic flaws, race conditions, cache poisoning/deception
- HTTP/2/3, request smuggling, parser differentials

### 🔐 Active Directory & Entra ID
- BloodHound with advanced Cypher queries
- Kerberos attacks: Kerberoasting, AS-REP Roasting, Pass-the-Ticket, Golden/Silver Tickets
- DCSync, RBCD, Shadow Credentials, AD CS (ESC1-ESC8)
- GPO analysis, delegation abuse, LAPS, DPAPI
- Lateral movement: Pass-the-Hash, WMI, PSExec, WinRM, DCOM

### 🐧 Linux Privilege Escalation
- SUID/SGID abuse, Sudo exploitation, capability abuse
- Kernel exploits (CVE-2025-40271, CVE-2026-43284, and more)
- Cron jobs, writable files, LD_PRELOAD hijacking
- Docker/LXC escape techniques
- Automated enumeration (LinPEAS, pspy)

### 🪟 Windows Privilege Escalation
- UAC bypass, SeImpersonate/SeBackup/SeRestore abuse
- Potato attacks (JuicyPotato, PrintSpoofer, GodPotato)
- Unquoted service paths, writable service binaries
- AlwaysInstallElevated, stored credentials
- Automated enumeration (WinPEAS, PowerUp, Seatbelt)

### ⚡ Binary Exploitation & Vulnerability Research
- ROP chain construction, ret2libc, ret2syscall
- Heap exploitation: TCache poisoning, UAF, House of X
- Format string attacks, canary bypass
- Fuzzing strategies, patch diffing, CVE research
- ASLR, DEP/NX, stack protections, CFI

### 🐳 Container & Kubernetes Security
- Docker escape (privileged containers, socket exposure)
- runc vulnerabilities (CVE-2025-31133, CVE-2025-52565, CVE-2025-52881)
- Kubernetes RBAC, service account abuse, admission controls
- Image provenance, registry security, secrets management

### ☁️ Cloud Security (AWS/Azure/GCP)
- IAM privilege escalation, misconfiguration discovery
- Metadata service abuse (IMDSv1/v2)
- S3 bucket enumeration, Azure Storage exposure
- GCP service account impersonation
- Cloud logging, incident readiness

### 🤖 AI & LLM Security
- Prompt injection, indirect prompt injection
- RAG security, vector database protection
- Tool/function calling authorization, agent security
- Model supply chain, data exfiltration through tools
- MCP (Model Context Protocol) security

### 🔀 Pivoting & Tunneling
- Ligolo-ng advanced tunneling
- SSH dynamic proxies, port forwarding
- Chisel SOCKS tunneling, SMB/NTLM relaying
- Proxychains, ADIDNS poisoning

### 🧬 AV/EDR Bypass
- AMSI bypass techniques
- Donut (EXE to shellcode conversion)
- Reflective injection, unmanaged PowerShell
- Process injection, memory-only payloads

### ⏳ Post-Exploitation
- Shell upgrades (TTY, Python, Socat)
- Credential dumping (Mimikatz, secretsdump, LSASS)
- Persistence mechanisms (Linux/Windows)
- Exfiltration techniques (Netcat, DNS, ICMP, HTTP/S)

### 📄 Reporting & Documentation
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

| Metric | Value |
|--------|-------|
| **Techniques** | 250+ |
| **Commands** | 150+ |
| **Attack Chains** | 12 |
| **Knowledge Domains** | 17 |
| **Languages Supported** | 12 |
| **Payload Combinations** | ∞ |

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

<p align="center">
  <a href="#npx20-overview"><img src="https://img.shields.io/badge/📋-Assessment_Compass-6fffe0?style=for-the-badge"/></a>
  <a href="#npx25-attack-tree"><img src="https://img.shields.io/badge/🌳-Discovery_Tree-a78bfa?style=for-the-badge"/></a>
  <a href="#npx26-command-center"><img src="https://img.shields.io/badge/⚡-Command_Center-6fffe0?style=for-the-badge"/></a>
</p>

<p align="center">
  <a href="#recon"><img src="https://img.shields.io/badge/🔍-Reconnaissance-a78bfa?style=for-the-badge"/></a>
  <a href="#enum"><img src="https://img.shields.io/badge/📡-Enumeration-6fffe0?style=for-the-badge"/></a>
  <a href="#v20-web-hub"><img src="https://img.shields.io/badge/🌐-Web_Attacks-a78bfa?style=for-the-badge"/></a>
  <a href="#ad-enum"><img src="https://img.shields.io/badge/🔐-Active_Directory-6fffe0?style=for-the-badge"/></a>
</p>

<p align="center">
  <a href="#privesc-linux"><img src="https://img.shields.io/badge/🐧-Linux_PrivEsc-a78bfa?style=for-the-badge"/></a>
  <a href="#privesc-windows"><img src="https://img.shields.io/badge/🪟-Windows_PrivEsc-6fffe0?style=for-the-badge"/></a>
  <a href="#binary"><img src="https://img.shields.io/badge/⚡-Binary_Exploitation-a78bfa?style=for-the-badge"/></a>
  <a href="#ports"><img src="https://img.shields.io/badge/📋-Ports_Reference-6fffe0?style=for-the-badge"/></a>
</p>

---

## 🌟 Why Arsenal?

> *"A quality defense requires knowing the offense, we provide security through understanding."*

Arsenal stands out because it's:

| ✅ **Research-Driven** | Built from the HackTricks wiki, community research, and real-world engagements |
|------------------------|-------------------------------------------------------------------------------|
| ✅ **Actionable**      | Every technique comes with practical commands and validation steps           |
| ✅ **Structured**      | Follows a clear methodology from scope to retest                            |
| ✅ **Modern**          | Covers 2025-2026 vulnerabilities, AI security, cloud, and containers        |
| ✅ **Accessible**      | Free, open-source, and available in 12 languages                            |

---

## 🤝 Contributing

Contributions are welcome! Whether it's fixing a typo, adding a new technique, or improving the structure:

1. 🍴 Fork the repository
2. ✏️ Make your changes
3. 📬 Submit a pull request

---

<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&duration=3500&pause=1000&color=6FFFE0&center=true&vCenter=true&width=600&lines=⭐+Star+the+repo+if+you+find+it+useful!;🐛+Report+issues;💡+Suggest+features;📚+Contribute+knowledge" alt="Typing SVG" />
</div>

<br>

<div align="center">

**🌙 NIGHT PULSE X · Arsenal**  
*Penetration Testing · Security Research · Future Ready*

</div>

---

*Part of the NIGHT PULSE X project family*
