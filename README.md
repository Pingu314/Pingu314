# Hey, I'm Pingu 👋

I'm based in **Zürich, Switzerland** - self-taught builder with a focus on **fraud detection and security analytics**.

My background is a bit unusual: construction apprenticeship, military service, self-employed in construction. Then two years of **24/7 fraud detection at a Swiss payment services provider** - live transaction monitoring, real-time pattern recognition during coordinated card fraud attacks, and cross-team escalation. That's where I learned what detection means in practice: separating signal from noise when it counts.

I build tools to understand the craft under the hood and it's the same craft whether the target is a fraudulent transaction, a phishing URL or a brute-force attempt: spot the pattern, score the risk, triage the case.

Currently studying for **CompTIA Security+** and learning **Splunk**.

---

### What I'm building

**[windows_event_analyzer](https://github.com/Pingu314/windows_event_analyzer)** - Detection and triage tool for Windows event logs. 107 SIGMA-style rules plus custom Sigma YAML across Security/Sysmon/Defender channels, incident correlation, threat-intel enrichment, live capture, HTML reports, MITRE ATT&CK mapping. 358 tests, 97% coverage. Python 3.10–3.14.

**[email_header_analyzer](https://github.com/Pingu314/email_header_analyzer)** - Python detection pipeline for phishing and spoofing via email header analysis. SPF/DKIM/DMARC verification, routing analysis, MIME evasion detection, MITRE ATT&CK mapping. Flask dashboard with verdict view, JSON/CSV/PDF export. 383 tests, 93% coverage. Python 3.9–3.14.

**[phishing_url_analyzer](https://github.com/Pingu314/phishing_url_analyzer)** - Python triage pipeline that detects phishing indicators in URLs, follows redirect chains, enriches with threat intel, assigns risk/confidence scores, maps to MITRE ATT&CK and exports reports. 125 tests, 95% coverage. Python 3.9–3.13.

**[soc_threat_analyzer](https://github.com/Pingu314/soc_threat_analyzer)** - Python detection pipeline for brute force, password spraying and impossible travel using SIGMA-based rules. Enriches alerts with threat intel, maps to MITRE ATT&CK sub-techniques, exports to CSV. Flask dashboard, multi-file ingestion. 118 tests, 93% coverage. Python 3.10–3.13.

**[Snake](https://github.com/Pingu314/Snake)** - Started as a single-file Turtle game (v1.0, frozen). Rewrote it from scratch as an ECS architecture with a state machine, theme engine, combo system and achievements (v1.1, in progress). Mostly just for fun.

---

### What I'm working with

`Python` · `SIGMA Rules` · `MITRE ATT&CK` · `Flask` · `pytest` · `Splunk` · `Git` · `Incident Correlation ` 

---

### Currently

- 📚 CompTIA Security+ (in progress)
- 🔵 TryHackMe SOC Level 1
- 📊 Splunk Core Certified User (in progress)
- 🛠️ Next: P5 orchestrator - unified triage across P1-P4

---

*Zürich 🇨🇭 · DE · EN · FR · "Code connects the world. Security keeps it safe."*
