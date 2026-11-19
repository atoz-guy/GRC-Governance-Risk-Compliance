# GRC: Governance, Risk and Compliance 

**Afiz (AJ) Jiwa** | UCSD graduate | Working toward ServiceNow GRC, SecOps and IRM implementation and architecture

This repo is where I keep my GRC work: framework notes, risk and compliance exercises, and links to the hands-on labs that back them up. My goal is to work in GRC with enough technical depth to understand the controls I'm auditing, not just the policy that asks for them.

---

## What I focus on

- **Frameworks:** NIST CSF, ISO 27001, SOC 2
- **Risk:** identifying risks, rating them by likelihood and impact, and tracking them in a risk register
- **Compliance:** gap analysis against a framework, control mapping, audit evidence
- **Policy:** turning a technical rule (for example "MFA is required for all admins") into a written policy someone can be held to
- **Platform:** ServiceNow Risk and Compliance (IRM), SecOps, Vulnerability Response
- **Threat modeling:** STRIDE for individual systems, PASTA when the conversation is about business impact
- **Linux:** hardening, access control and logging checks, since a lot of compliance comes down to how servers are set up
- **Data:** cleaning and analyzing security data with SQL, pandas and Power BI

---

## In my own words

**Why GRC?**
I like seeing how everything connects. Security tools tell you something is wrong. GRC asks whether it matters, who owns it, and whether we can prove it's handled.

**Why do you care so much about data?**
Because security work is only as good as the data under it. ServiceNow won't even let you take the SIR or VR exams without Data Foundations first, and that makes sense. If the asset data is wrong, the incident goes to the wrong team and the vulnerability gets ranked wrong.

**What part do you like that others skip?**
Getting the data right. Cleaning up records with SQL and pandas isn't exciting. It's like a long drive: fun for the first five minutes, then you just keep going because you know where you're headed. But that's what makes the results something people can trust.

---

## Certifications

**ServiceNow**
- Certified System Administrator (CSA), June 2026
- CIS Risk and Compliance (CIS-RC), July 2026
- **Security Operations (SecOps)**
  - CIS Data Foundations (CIS-DF), Oct 2026: required before SIR and VR
  - CIS Security Incident Response (CIS-SIR), Oct 2026
  - CIS Vulnerability Response (CIS-VR), Oct 2026

**Microsoft**
- SC-100: Cybersecurity Architect Expert
- SC-300: Identity and Access Administrator Associate
- SC-401: Information Security Administrator Associate
- AZ-104: Azure Administrator Associate
- PL-300: Power BI Data Analyst Associate

**Security and Cloud**
- CompTIA Security+, Linux+, SecAI+
- AWS Solutions Architect Associate (SAA-C03)
- LPIC-1

**Google**
- Google Cybersecurity
- Google IT Support (through the San Diego Workforce Partnership "Cybersecurity & IT Support" program)
- Google IT Automation with Python
- Google Data Analytics

**Python**
- PCEP, PCAP, PCPP1

**ISACA**
- CRISC: exam passed
- CISM: up next
- CISA: planned

**Looking ahead (about 2 years)**
- CompTIA CySA+
- LPIC-2

---

## Projects

| Project | What it shows |
|---|---|
| [grc-portfolio](https://github.com/atoz-guy/grc-portfolio) | Excel GRC tools: CMMC Level 1 readiness dashboard and IAM & API access hygiene scorecard, each with a 2-page executive summary |
| [Python-Automation-Lab](https://github.com/atoz-guy/Python-Automation-Lab) | GRC audit and ticket logger written in Python |
| [Microsoft 365 labs](https://github.com/atoz-guy/Cybersecurity-Technical-Portfolio/tree/main/Cloud-Security-Labs/M365) | Purview DLP, sensitivity labels, Compliance Manager, retention, Entra |
| [Azure labs](https://github.com/atoz-guy/Cybersecurity-Technical-Portfolio/tree/main/Cloud-Security-Labs/Azure) | AZ-104: RBAC, subscriptions, hub-and-spoke networking |
| [Forward-Deployed-Identity-Security](https://github.com/atoz-guy/Cybersecurity-Technical-Portfolio/tree/main/Forward-Deployed-Identity-Security) | Work in progress: CyberArk PAM, Entra and ServiceNow integration |
| [ServiceNow-](https://github.com/atoz-guy/ServiceNow-) | ServiceNow projects tied to my certifications |
| [Cybersecurity-Technical-Portfolio](https://github.com/atoz-guy/Cybersecurity-Technical-Portfolio) | SOC labs plus GRC-Labs: a credential phishing investigation (after it happens) and policy-as-code labs (before it happens) |

---

## What's coming to this repo

- [ ] NIST CSF gap analysis of a small business (my own store, ATOZ Cyber Labs)
- [ ] Risk register with likelihood and impact scoring
- [ ] Sample information security policy set (access control, MFA, acceptable use)
- [ ] Control mapping: framework requirement to technical control to evidence source
- [ ] STRIDE threat model for one system with a data flow diagram

---

## Roadmap

See [Pathway.md](Pathway.md) for my certification and learning plan.

I'm also learning healthcare GRC (HIPAA). My reading path and notes are in [Healthcare-GRC](Healthcare-GRC).
