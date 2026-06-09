# Threat Hunt Portfolio

**Analyst:** Joshua Fischer  
**Platform:** Microsoft Sentinel + KQL  
**Methodology:** Hypothesis-Driven Threat Hunting

---

## Available Reports

### SILENT CORRIDOR
- **Date:** 09 May 2026
- **Threat Actor:** GREY VEIL (Defence Sector APT)
- **Level:** Advanced
- **Status:** SOLVED — 37/37 Flags
- **Global Rank:** #2

**Summary:** Proactive threat hunt against a state-sponsored APT targeting European aerospace and defence contractors. Full attack chain reconstruction from credential testing via Tor exit node through to data exfiltration. Zero custom tooling — entirely living-off-the-land.

**Key Findings:**
- LSASS memory dump + SAM hive extraction
- NTDS.DIT extraction via ntdsutil IFM
- WMI-based lateral movement
- Port proxy persistence mechanism
- A400M avionics data exfiltrated

---

## Structure

```
threat-hunt-portfolio/
├── index.html              # Portfolio overview
├── README.md
├── silent-corridor/
│   └── index.html          # Full hunt report
└── [future-hunt]/
    └── index.html
```

## Live Site

Hosted via GitHub Pages:

```
https://joshua-jeremy-fischer.github.io/threat-hunt-portfolio/
```

---

*Built with GitHub Pages. No build tools, no dependencies — pure HTML/CSS.*