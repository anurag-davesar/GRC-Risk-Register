# Enterprise Risk Register — ABC Company (Fictitious)

A cybersecurity risk assessment simulating the work of a GRC Analyst: identifying risks, scoring them by likelihood and impact, mapping them to the NIST Cybersecurity Framework (CSF) 2.0, and recommending treatment plans.

## 📌 Objective

This project simulates a risk assessment exercise for a fictitious mid-size organization, **ABC Company**. The goal was to identify realistic cybersecurity risks across people, process, and technology domains, score them using a standard likelihood × impact methodology, and produce a risk register that could plausibly be used by a real security or GRC team to prioritize remediation.

## 🧭 Methodology

Each risk was scored using a **5x5 risk matrix**:

| Impact Level | Value | Likelihood Level | Value |
|---|---|---|---|
| Negligible | 1 | Rare | 1 |
| Minor | 2 | Unlikely | 2 |
| Moderate | 3 | Possible | 3 |
| Major | 4 | Likely | 4 |
| Critical | 5 | Almost Certain | 5 |

**Risk Rating = Impact × Likelihood**

| Rating | Score Range |
|---|---|
| Low | 1–5 |
| Moderate | 6–10 |
| High | 11–15 |
| Extreme | 16–25 |

Each risk was also mapped to relevant **NIST CSF 2.0 functions** (e.g., `PR.AA` – Identity & Access Control, `RS.MI` – Mitigation, `GV.SC` – Supply Chain Risk Management) to tie remediation back to a recognized industry framework, and assigned to a named risk owner/role reflecting realistic organizational accountability.

## 📊 Scope

- **15 risks** assessed across the organization
- **Risk categories covered:** Phishing/Social Engineering, Malware/Ransomware, Third-Party Risk, Data Breach, Insider Threat, System Misconfiguration, Access Control Failure, Denial of Service
- **Rating distribution:** includes Low, Moderate, High, and Extreme risks — reflecting a realistic mixed-severity environment rather than a worst-case-only list

## 🗂️ Register Structure

Each entry in the register includes:

- **Risk No.** — unique identifier (R001–R015)
- **Risk Title** — short descriptive name
- **Affected Asset** — system, data, or infrastructure impacted
- **Risk Description** — what could happen
- **Likelihood** — qualitative rating
- **Potential Impact / Risk Rating** — numeric score and severity tier
- **Risk Category** — threat classification
- **Risk Owner** — accountable role (e.g., CISO, Head of IAM, SOC Manager)
- **NIST CSF 2.0 Alignment** — mapped framework function(s)
- **Recommended Treatment** — specific mitigation or remediation action

## 🔍 Sample Entries

| Risk No. | Risk Title | Rating | NIST CSF Alignment | Owner |
|---|---|---|---|---|
| R001 | Phishing Email to Staff | Extreme | PR.PS, PR.AA, PR.AT | CISO |
| R004 | Stolen Contractor Credentials | Extreme | RS.MI, PR.AA | Head of IAM |
| R005 | Open S3 Bucket Exposed | High | PR.DS, PR.PS | Cloud Infrastructure Manager |
| R010 | Lateral Movement Detected | Extreme | RS.MI, DE.CM | SOC Manager |
| R011 | Unlocked Server Cabinet | Low | PR.PS, DE.CM | Physical Security Manager |

Full register: [`Risk_Register.xlsx`](./Risk_Register.xlsx)

## 🎯 Skills Demonstrated

- Risk identification and threat categorization
- Quantitative risk scoring (likelihood × impact methodology)
- Control mapping to the NIST Cybersecurity Framework 2.0
- Risk ownership and accountability assignment
- Risk treatment planning (mitigation, remediation, and monitoring recommendations)
- Structuring a risk register to real-world GRC reporting standards

## 🛠️ Tools Used

- Microsoft Excel — risk scoring, categorization, and register formatting
- NIST CSF 2.0 — control framework reference

## 📁 Files

- `Risk_Register.xlsx` — full risk register with scoring matrix and legend

---

*This is a portfolio project using a fictitious company and simulated risk scenarios. It is intended to demonstrate GRC analyst methodology and is not based on any real organization's data.*
