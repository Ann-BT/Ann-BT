<h1 align="center">Bùi Trường An (Merlin)</h1>
<p align="center">
  <b>Cybersecurity Student · Aspiring SOC Analyst · Blue Team</b><br/>
  University of Science and Technology of Hanoi (USTH) · Cầu Giấy, Hà Nội
</p>

<p align="center">
  <a href="mailto:anbt.personal@gmail.com"><img src="https://img.shields.io/badge/Email-anbt.personal%40gmail.com-red?style=flat-square&logo=gmail&logoColor=white"/></a>
  <a href="https://linkedin.com/in/ann-bt"><img src="https://img.shields.io/badge/LinkedIn-ann--bt-0077B5?style=flat-square&logo=linkedin&logoColor=white"/></a>
  <a href="https://www.facebook.com/merlinthegreatmage"><img src="https://img.shields.io/badge/Facebook-Merlin-1877F2?style=flat-square&logo=facebook&logoColor=white"/></a>
  <img src="https://komarev.com/ghpvc/?username=Ann-BT&style=flat-square&color=grey" alt="profile views"/>
</p>

---

## `> whoami`

Cybersecurity student building real tools, not just studying theory.  
My focus is **Blue Team** — threat detection, log analysis, behavioral analysis, and SOC workflows.  
Currently interning at **ICTLab USTH** and actively developing [SIDERIS](https://github.com/Ann-BT/SIDERIS).

- `[edu]` Bachelor in Cyber Security @ USTH — Top 3 Year 1, 3-year scholarship
- `[focus]` Detection engineering, WAF design, and security automation
- `[os]` CachyOS (Arch Linux) — daily driver, CLI-native
- `[lang]` Comfortable working entirely in English

---

## `> cat SIDERIS.md`

> **Real-time Web Attack Detection & Behavioral Analysis Platform**

A production-style sidecar WAF and SOC platform I built from scratch.  
Reverse-proxies existing web apps, injects a client-side telemetry beacon, and scores every session in real time.

| Component | What it does |
|---|---|
| `agent.js` | Client-side beacon — keystroke dynamics, cursor liveness, bot fingerprinting |
| Detection worker | Consumes Redis Streams, applies **Impact × Confidence × Persistence** heuristic scoring |
| Guard service | Atomic Redis Lua enforcement — block / challenge / rate-limit with dynamic TTL penalty scaling |
| SOC Dashboard | Live session monitoring, manual overrides, attack category charts, report download |

**Stack:** Node.js · React/Vite · Redis Streams · Express.js · Docker  
**Coverage:** 14 attack signatures · 13 compound bonus rules · 5 enforcement tiers · aligned with OWASP Top 10

[![SIDERIS](https://img.shields.io/badge/GitHub-SIDERIS-181717?style=for-the-badge&logo=github)](https://github.com/Ann-BT/SIDERIS)

---

## `> ls projects/`

**Phish Shield** — Browser extension with ML-based phishing URL detection (Random Forest + blacklist/whitelist)

**Chronos Pentest (VulnHub)** — Full recon-to-root: broken access control via User-Agent, unauthenticated RCE via command injection, privilege escalation via sudo misconfiguration

**CVE-1999-0497** — Reproduced anonymous FTP login vulnerability in lab, performed network scan, remediated with firewall rules

**Secure SMS OTP System** — 2FA service using Python Flask, Redis (TTL-enforced OTP), Twilio

---

## `> cat skills.txt`

**Security (hands-on):**  
`Wireshark` `Burp Suite` `OWASP ZAP` `PEStudio` `IDA Pro` `Process Monitor` `Wazuh`

**Practices:**  
Threat detection · Behavioral analysis · Log & network traffic analysis · Static malware triage · Web application security (OWASP Top 10) · Penetration testing · Digital forensics

**Development:**  
`Node.js` `JavaScript` `Python` `Redis` `Docker` `Express.js` `React`

**OS:**  
Linux (CachyOS/Arch — daily driver) · Windows

---

## `> ls certs/`

<details>
<summary><b>Google Cybersecurity Professional Certificate</b> — 9 courses · Coursera · Dec 2025</summary>
<br/>

> Verify: https://coursera.org/verify/professional-cert/8N7V01K25JQK

<table>
<tr>
<td align="center" width="50%">
<img src="https://github.com/Ann-BT/Ann-BT/blob/main/certs/Coursera_cybersecurity.png?raw=true" width="380"/>
<br/><sub>Google Cybersecurity — Professional Certificate</sub>
</td>
<td align="center" width="50%">
<img src="https://github.com/Ann-BT/Ann-BT/blob/main/certs/cert_coursera_.png?raw=true" width="380"/>
<br/><sub>Foundations of Cybersecurity</sub>
</td>
</tr>
<tr>
<td align="center">
<img src="https://github.com/Ann-BT/Ann-BT/blob/main/certs/Coursera_play_it_safe.png?raw=true" width="380"/>
<br/><sub>Play It Safe: Manage Security Risks</sub>
</td>
<td align="center">
<img src="https://github.com/Ann-BT/Ann-BT/blob/main/certs/Coursera_connect_and_protect.png?raw=true" width="380"/>
<br/><sub>Connect and Protect: Networks and Network Security</sub>
</td>
</tr>
<tr>
<td align="center">
<img src="https://github.com/Ann-BT/Ann-BT/blob/main/certs/Coursera_Tool_of_trade.png?raw=true" width="380"/>
<br/><sub>Tools of the Trade: Linux and SQL</sub>
</td>
<td align="center">
<img src="https://github.com/Ann-BT/Ann-BT/blob/main/certs/Coursera_threats.png?raw=true" width="380"/>
<br/><sub>Assets, Threats, and Vulnerabilities</sub>
</td>
</tr>
<tr>
<td align="center">
<img src="https://github.com/Ann-BT/Ann-BT/blob/main/certs/Coursera_Sound_of_alarm.png?raw=true" width="380"/>
<br/><sub>Sound the Alarm: Detection and Response</sub>
</td>
<td align="center">
<img src="https://github.com/Ann-BT/Ann-BT/blob/main/certs/Coursera_python.png?raw=true" width="380"/>
<br/><sub>Automate Cybersecurity Tasks with Python</sub>
</td>
</tr>
<tr>
<td align="center">
<img src="https://github.com/Ann-BT/Ann-BT/blob/main/certs/Coursera_put_it_to_work.png?raw=true" width="380"/>
<br/><sub>Put It to Work: Prepare for Cybersecurity Jobs</sub>
</td>
<td align="center">
<img src="https://github.com/Ann-BT/Ann-BT/blob/main/certs/Coursera_AI.png?raw=true" width="380"/>
<br/><sub>Accelerate Your Job Search with AI</sub>
</td>
</tr>
<tr>
<td align="center" colspan="2">
<img src="https://github.com/Ann-BT/Ann-BT/blob/main/certs/Coursera_CISO.png?raw=true" width="380"/>
<br/><sub>Office of the CISO Institute: Cybersecurity Essentials</sub>
</td>
</tr>
</table>
</details>

---

<details>
<summary><b>Fortinet Certifications</b> — NSE · Cybersecurity · FortiGate</summary>
<br/>

<table>
<tr>
<td align="center" width="50%">
<img src="https://github.com/Ann-BT/Ann-BT/blob/main/certs/Fortinet_Certified_Associate_in_Cybersecurity.png?raw=true" width="380"/>
<br/><sub>Fortinet Certified Associate in Cybersecurity</sub>
<br/><sup>Valid until Dec 17, 2027 · #7698225744TA</sup>
</td>
<td align="center" width="50%">
<img src="https://github.com/Ann-BT/Ann-BT/blob/main/certs/Fortinet_Certified_Fundamentals_in_Cybersecurity.png?raw=true" width="380"/>
<br/><sub>Fortinet Certified Fundamentals in Cybersecurity</sub>
<br/><sup>Valid until Dec 17, 2027 · #8667986744TA</sup>
</td>
</tr>
<tr>
<td align="center">
<img src="https://github.com/Ann-BT/Ann-BT/blob/main/certs/FortiGate_7_6_Operator_Self-Paced.png?raw=true" width="380"/>
<br/><sub>FortiGate 7.6 Operator</sub>
</td>
<td align="center">
<img src="https://github.com/Ann-BT/Ann-BT/blob/main/certs/Getting_Started_in_Cybersecurity_3_0.png?raw=true" width="380"/>
<br/><sub>Getting Started in Cybersecurity 3.0</sub>
</td>
</tr>
<tr>
<td align="center">
<img src="https://github.com/Ann-BT/Ann-BT/blob/main/certs/Technical_Introduction_to_Cybersecurity_3_0.png?raw=true" width="380"/>
<br/><sub>Technical Introduction to Cybersecurity 3.0</sub>
</td>
<td align="center">
<img src="https://github.com/Ann-BT/Ann-BT/blob/main/certs/NSE_1.png?raw=true" width="380"/>
<br/><sub>Introduction to the Threat Landscape 3.0</sub>
</td>
</tr>
</table>
</details>

---

<details>
<summary><b>Cisco Networking Academy</b> — Network Defense · Dec 2025</summary>
<br/>

<p align="center">
<img src="https://github.com/Ann-BT/Ann-BT/blob/main/certs/Network_Defense.png?raw=true" width="500"/>
<br/><sub>Cisco: Network Defense — Dec 22, 2025</sub>
</p>
</details>

---

<details>
<summary><b>F8 — fullstack.edu.vn</b> — HTML & CSS · Ubuntu with WSL</summary>
<br/>

<table>
<tr>
<td align="center" width="50%">
<img src="https://github.com/Ann-BT/Ann-BT/blob/main/certs/cert_html.png?raw=true" width="380"/>
<br/><sub>HTML & CSS — Oct 12, 2022</sub>
</td>
<td align="center" width="50%">
<img src="https://github.com/Ann-BT/Ann-BT/blob/main/certs/cert_wsl.png?raw=true" width="380"/>
<br/><sub>Ubuntu with WSL — Feb 28, 2025</sub>
</td>
</tr>
</table>
</details>

---

## `> locale`

English — B2 (certified by USTH) &nbsp;|&nbsp; French — A2 (TCF) &nbsp;|&nbsp; Vietnamese — Native

---

<p align="center"><i>"Security is not a product, but a process."</i></p>
