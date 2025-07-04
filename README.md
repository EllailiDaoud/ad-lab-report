# Setting Up and Securing an Active Directory Lab

**Authors:** Daoud Ellaili · Oualid Daouche  
Date: 03 July 2025  

---

## Overview
This repository contains the full write-up of our project where we built a virtual
Active Directory environment and hardened it against common attack techniques.

| Component | Purpose |
|-----------|---------|
| **Windows Server 2019** | Domain Controller (AD DS, DNS) |
| **Windows 10** | Domain-joined workstation |
| **Splunk (Ubuntu)** | Centralised log collection & SIEM |
| **Kali Linux** | Attacker box for BloodHound, Mimikatz, CME |

We cover installation, Group Policy hardening (LAPS, audit settings), attack
simulation, and log-based detection with Splunk.

---

## 📄 Project Report

Download / view the full 35-page PDF here ➜  
`Setting_Up_and_Securing_an_Active_Directory_Lab.pdf`

---

## Quick start

```bash
# clone the repo
git clone https://github.com/<your-user>/ad-lab-report.git
open ad-lab-report/Setting_Up_and_Securing_an_Active_Directory_Lab.pdf


