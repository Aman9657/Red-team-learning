# FakeBank — Directory Enumeration (dirb) — Learning Report

**Platform:** TryHackMe — Pre-Security Path  
**Room / Lab:** Offensive Security Intro — FakeBank (guided exercise)  

---

## Briefing
The lab objective was to demonstrate how attackers may find hidden website features by checking for unlinked directories (secret URLs) in a controlled environment.

---

## Tool used (as presented in the lab)
**dirb** — used in the guided lab to test a list of common directory names against the FakeBank web application.

---

## Steps performed (what I actually did)
1. Started the FakeBank lab environment on TryHackMe.  
2. Opened the terminal provided in the lab interface.  
3. Executed `dirb` against the target URL to enumerate common directories (as instructed by the guided task).  
4. Reviewed the `dirb` output to identify any discovered paths.  
5. Did not perform any further exploitation beyond the guided demonstration.

> Note: This was a guided learning exercise run only in the TryHackMe lab environment. No real systems were targeted and no sensitive outputs (flags or credentials) are included.

---

## What I learned (from the lab)
- Directory enumeration can reveal hidden endpoints that may not be linked from a website’s main pages.  
- Tools like `dirb` automate the process of checking common path names, which speeds up reconnaissance in a safe lab environment.  
- Guided exercises are useful to understand the concept without applying it outside of legal lab environments.

---

## Evidence
Screenshots were intentionally omitted in this report to avoid exposing lab-specific outputs. I can add sanitized screenshots later if I re-run the lab and ensure no flags/credentials are visible.
