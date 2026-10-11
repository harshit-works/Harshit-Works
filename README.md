<div align="center">

<img src="./banner.svg" alt="Harshit Thakur - Aspiring SOC Analyst" width="100%">

<br>

![Status](https://img.shields.io/badge/STATUS-BUILDING%20TOWARDS%20SOC%20ROLES-00c853?style=for-the-badge)
![TryHackMe](https://img.shields.io/badge/TryHackMe-Top%205%25-red?style=for-the-badge&logo=tryhackme&logoColor=white)
![SOC L1](https://img.shields.io/badge/SOC%20Level%201-in%20progress-212c42?style=for-the-badge)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/harshit-thakur-infosec/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:harshitthakur.2206@gmail.com)
[![TryHackMe](https://img.shields.io/badge/TryHackMe-212c42?style=for-the-badge&logo=tryhackme&logoColor=white)](https://tryhackme.com/p/severuss)

</div>

---

## 🛡️ $ whoami

```yaml
  name       : Harshit Thakur
  role       : BCA student · aspiring SOC Analyst (Tier 1)
  location   : Madhya Pradesh, India
  education  : BCA, Barkatullah University, Bhopal
  focus      : [ Log Analysis, Alert Triage, Threat Detection, Incident Response ]
  tools      : [ Splunk (SPL), Wazuh, Wireshark, Python, Linux ]
  next_up    : MCA, then deeper systems and detection engineering
  looking_for: SOC internships
```


I’m a BCA student training for a SOC analyst role. I’m learning to read logs, triage alerts, and explain what happened and why, and I practice on TryHackMe and LetsDefend. I’m building a home SIEM lab with Wazuh, using Kali to simulate attacks and Windows and Metasploitable as targets, so I can investigate real alerts from attack to conclusion. I already know Python and Linux, and I’m using them to automate log analysis. Every investigation I finish gets written up on this profile.


## 📊 Progress (updated as I go)

| TryHackMe | LetsDefend | Home lab | Case studies |
|:--:|:--:|:--:|:--:|
| Pre Security, Cyber Security 101 done · SOC L1 in progress | 1 alerts so far | planned | 1 published |

---

## 🔎 $ cat how_i_investigate.md

`Alert → Scope (host, user, IP, time) → Evidence in logs → True/False positive → Timeline → Recommendation`

Real write-ups will be linked here as I publish them.

---

## 📈 $ git log --stats

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=harshit-works&show_icons=true&theme=chartreuse-dark&hide_border=true)
![Streak](https://streak-stats.demolab.com?user=harshit-works&theme=dark&hide_border=true)

---

## 🧭 $ cat soc_playbook.md — how I plan to handle an alert

```mermaid
flowchart LR
    A[Alert fires<br/>SIEM] --> B[Triage<br/>host, user, IP, time]
    B --> C{Suspicious?}
    C -- No --> D[Close as false positive<br/>note the reason]
    C -- Yes --> E[Enrich<br/>logs, threat intel, ATT&CK]
    E --> F[Build timeline]
    F --> G[Escalate to Tier 2<br/>with evidence]
```
# SOC Investigations

Alert investigations from LetsDefend and my home lab. Each write-up follows
Scenario → Evidence → Timeline → Finding → Recommendation.

| # | Alert | Type | Verdict | MITRE |
|---|---|---|---|---|
| 1 | [SOC335: CVE-2024-49138 exploitation](letsdefend/soc335-cve-2024-49138/) | Privilege escalation | True positive | T1036, T1068 |

---

## 📒 $ cat training.log

```
[2026] TryHackMe: Pre Security, Cyber Security 101 completed
[2026] TryHackMe: SOC Level 1 in progress
[2026] Splunk (SPL) basics completed
[NEXT] LetsDefend alert investigations
[NEXT] Home SIEM lab (Wazuh + Kali + Windows + Metasploitable)
[NEXT] 3 case studies: phishing, endpoint detection, network threat hunt
```

---

## ⚔️ $ cat ./arsenal.conf

<table>
<tr>
<td width="50%" valign="top">

**🔵 Blue Team: Detect & Respond**

![Splunk](https://img.shields.io/badge/Splunk-000000?style=flat-square&logo=splunk&logoColor=white)
![Wazuh](https://img.shields.io/badge/Wazuh-in%20progress-005571?style=flat-square)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white)
![MITRE](https://img.shields.io/badge/MITRE%20ATT%26CK-learning-c8102e?style=flat-square)

<sub>Log analysis · alert triage · SPL searches · traffic analysis</sub>

</td>
<td width="50%" valign="top">

**🔴 Red Team: Basics**

![Kali](https://img.shields.io/badge/Kali%20Linux-557C94?style=flat-square&logo=kalilinux&logoColor=white)
![Nmap](https://img.shields.io/badge/Nmap-4B0082?style=flat-square)
![Burp](https://img.shields.io/badge/Burp%20Suite-FF6633?style=flat-square&logo=portswigger&logoColor=white)

<sub>Recon and web testing fundamentals. Deeper offensive work comes later.</sub>

</td>
</tr>
<tr>
<td width="50%" valign="top">

**💻 Code & Data**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

<sub>Scripting for log parsing and automation</sub>

</td>
<td width="50%" valign="top">

**🧭 Learning Next**

![Sigma](https://img.shields.io/badge/Sigma%20rules-planned-555555?style=flat-square)
![Atomic](https://img.shields.io/badge/Atomic%20Red%20Team-planned-555555?style=flat-square)
![Zeek](https://img.shields.io/badge/Zeek-planned-555555?style=flat-square)

<sub>Detection engineering and threat hunting</sub>

</td>
</tr>
</table>

---

## 📜 $ cat ./certifications.log

<details open>
<summary><b>🔐 Cybersecurity</b></summary>

| Certification | Issuer | Date |
|---|---|---|
| Cyber Security 101 | TryHackMe | 2026 |

</details>

<details>
<summary><b>🐍 Data & AI</b></summary>

| Certification | Issuer | Date |
|---|---|---|
| Python for Data Science | Cognitive Class | Jan 2025 |
| BCG GenAI Job Simulation | Forage | Jan 2025 |

</details>

<details>
<summary><b>🌐 Networking</b></summary>

| Certification | Issuer | Date |
|---|---|---|
| Add your Cisco course once you finish it | Cisco Networking Academy | |

</details>

---

## 🧪 Projects
Coming soon: Python log analyzer, Wazuh home lab, SOC case studies.
