```
 ██████╗██╗   ██╗██████╗ ███████╗██████╗
██╔════╝╚██╗ ██╔╝██╔══██╗██╔════╝██╔══██╗
██║      ╚████╔╝ ██████╔╝█████╗  ██████╔╝
██║       ╚██╔╝  ██╔══██╗██╔══╝  ██╔══██╗
╚██████╗   ██║   ██████╔╝███████╗██║  ██║
 ╚═════╝   ╚═╝   ╚═════╝ ╚══════╝╚═╝  ╚═╝
██████╗  ██████╗  ██████╗ ██╗   ██╗███████╗██╗     ██╗██╗  ██╗███████╗
██╔══██╗██╔═══██╗██╔════╝ ██║   ██║██╔════╝██║     ██║██║ ██╔╝██╔════╝
██████╔╝██║   ██║██║  ███╗██║   ██║█████╗  ██║     ██║█████╔╝ █████╗
██╔══██╗██║   ██║██║   ██║██║   ██║██╔══╝  ██║     ██║██╔═██╗ ██╔══╝
██║  ██║╚██████╔╝╚██████╔╝╚██████╔╝███████╗███████╗██║██║  ██╗███████╗
╚═╝  ╚═╝ ╚═════╝  ╚═════╝  ╚═════╝ ╚══════╝╚══════╝╚═╝╚═╝  ╚═╝╚══════╝
```

## *A procedurally generated cybersecurity text adventure*

---

You are a **red team operator**. Your mission: **breach NexaCorp**. Real MITRE ATT&CK techniques. Real CVEs. Real tactics. *How deep can you go?*

Every run is different. Every network is procedurally generated. The blue team is watching. The clock is ticking. One wrong move and you're burned.

---

## ✨ Features

- 🎲 **Procedural Generation** — Every target network is unique. Different hosts, services, vulnerabilities, and defenses each run.
- 🗡️ **Real ATT&CK Techniques** — Use actual MITRE ATT&CK tactics and techniques mapped to the kill chain. Learn while you play.
- 🎯 **Skill Checks** — Success isn't guaranteed. Your operator's skills, tools, and choices determine outcomes.
- 🤖 **Blue Team AI** — An adaptive defender watches for anomalies. Trigger too many alerts and incident response kicks in.
- 💎 **Loot System** — Discover exploits, credentials, zero-days, and tools. Build your arsenal across the engagement.
- 🔍 **Detection Mechanics** — Every action has a noise level. Stealth matters. Logs are real. SIEM rules fire.
- 🏆 **Rankings** — Compete for the highest operator rating. Speed, stealth, and depth all count.

---

## 🎮 How To Play

Navigate NexaCorp's network using text commands:

| Command | Description |
|---------|-------------|
| `scan <target>` | Enumerate a host or subnet |
| `exploit <cve>` | Attempt to exploit a vulnerability |
| `pivot <host>` | Move laterally to another host |
| `escalate` | Attempt privilege escalation |
| `exfil <data>` | Exfiltrate discovered data |
| `hide` | Cover your tracks and reduce detection |
| `tools` | View your current toolkit |
| `status` | Check alert level and position |
| `help` | Show all available commands |

---

## 🏆 Scoring & Rankings

| Rank | Title | Score Range |
|------|-------|-------------|
| 🥇 | **APT Operator** | 10,000+ |
| 🥈 | **Red Team Lead** | 7,500 – 9,999 |
| 🥉 | **Pentester** | 5,000 – 7,499 |
| 🔵 | **Script Kiddie** | 2,500 – 4,999 |
| ⚪ | **Intern** | 0 – 2,499 |

Points are awarded for depth of access, data exfiltrated, stealth maintained, and techniques used. Bonus points for staying undetected.

---

## 🚀 Quick Start

**Option 1** — Just open the file:
```
open index.html
```

**Option 2** — Serve it locally:
```bash
python3 -m http.server 5002
# Then visit http://localhost:5002
```

**Option 3** — Use the included server:
```bash
python3 server.py
# Serves on http://localhost:5002
```

---

## 📚 Educational Value

This game is designed to teach real cybersecurity concepts through gameplay:

- **MITRE ATT&CK Framework** — Every technique in the game maps to a real ATT&CK technique ID. Learn tactics, techniques, and procedures (TTPs) as you play.
- **Real CVEs** — Vulnerabilities are based on actual CVE entries. Understand what makes software exploitable.
- **Attack Lifecycle** — Experience the full kill chain: reconnaissance → initial access → execution → persistence → privilege escalation → lateral movement → exfiltration.
- **Defender Perspective** — The blue team AI shows you what detection looks like from the other side. Understand how SOC analysts catch attackers.

*Play offense. Learn defense.*

---

## 🎨 Part of the Creative Suite

**Project 4 of 5** in the QuietRiverTech Creative Suite — a collection of interactive experiences that make complex topics approachable and fun.

---

## 📄 License

MIT License · Copyright 2026 [QuietRiverTech](https://github.com/QuietRiverTech)

Built with ☕ by **QuietRiverTech**
