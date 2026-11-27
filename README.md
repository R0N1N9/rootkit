# Rootkit

A hacking game and hands-on cyber training sim in a single HTML file. It runs in any modern browser on a phone or a laptop.

## Command-line training

20 missions in a simulated Linux terminal. You type real commands (`ls`, `grep`, `awk`, `nmap`, `ssh`, `sudo`, `ss`, `ufw`, `sha256sum`, `strings`, `dig`, `whois` and more) against a fictional filesystem and network. Every command has a `man` page, and each mission has a briefing, objectives with hints, and a debrief on how the skill is used on the job.

| Track | Goal role | Missions |
|---|---|---|
| Red Team | Junior penetration tester | Shell fundamentals · Recon inside the rules · First foothold · Privilege escalation checks |
| Blue Team | SOC analyst tier 1 / sysadmin | Log analysis · Incident response · Hardening baseline · Web attack triage |
| Threat Intel | Junior CTI analyst | Indicators & tradecraft · Phishing analysis · Attribution · Intel for decision-makers |
| Counterintelligence | Insider threat / CI analyst | OPSEC footprint review · Insider threat investigation · Deception & canary tokens · Spotting targeting early |
| AI Security | AI security analyst | Prompt injection incident · Excessive agency & leaky prompts · Model supply chain · Evals & guardrails |

Everything is simulated. Every IP comes from a documentation range, and every company, person and threat actor is invented. MITRE ATT&CK and the OWASP Top 10 for LLM Applications are referenced by their real IDs.

## Quick play

A tap-to-hack network map: scan, exploit, crack, escalate, harvest and cover your tracks, while a defender patches, firewalls, restores and plants honeypots.

- **Sandbox** and **vs. AI Defender** (one player)
- **Split Screen** on one device: a face-off with each player at one end of the screen
- **Co-op**, **Attack & Defend**, **Duel (1v1)** and **Split Screen** between two devices

## Themes

Settings has five themes: Classic, Netrunner, Phosphor, Amber and Arctic. There's also an option to tint each mission with its track's colour and a switch for screen effects.

## Running it

Open `index.html` in a browser. Training and the single-device modes work offline.

Two-device play uses the `room` capability of Claude artifacts, so it only works when the page is published as an artifact on claude.ai and both players open it there, signed in.
