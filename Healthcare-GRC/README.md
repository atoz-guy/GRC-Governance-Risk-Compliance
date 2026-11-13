# Healthcare GRC

*Learning in progress.* I'm building toward GRC work in healthcare. My starting point is real: I've worked in data entry and hospital billing, so I've handled patient information on the job. This folder is where I learn the security and compliance side of it.

---

## The basics

**HIPAA** protects patient health information. For security work, the part that matters most is the **HIPAA Security Rule**, which covers electronic health information (ePHI).

The Security Rule is built on three kinds of safeguards:

| Safeguard | What it means | Example |
|---|---|---|
| **Administrative** | Policies, people and processes | Risk analysis, security training, assigning a security officer |
| **Physical** | Protecting the actual places and devices | Locked server rooms, workstation placement, disposing of old drives |
| **Technical** | Settings and tools in the systems | Access controls, audit logs, encryption, unique user IDs |

**Required vs addressable:** some specifications are *required* (you must do them). Others are *addressable*, which means you decide if they're reasonable for your organization and document why. The current rule doesn't specifically require MFA.

---

## Reading path

| # | Read | Why |
|---|---|---|
| 1 | [HHS: Summary of the HIPAA Security Rule](https://www.hhs.gov/ocr/privacy/hipaa/understanding/srsummary.html) | The official plain-language overview. Start here. |
| 2 | [NIST SP 800-66 Rev 2](https://csrc.nist.gov/pubs/sp/800/66/r2/final) | NIST's guide to implementing the Security Rule (Feb 2024). Maps HIPAA to NIST CSF and SP 800-53, which I already know. Also covers how to do a HIPAA risk analysis. |
| 3 | [HHS: Fact sheet on the proposed Security Rule update](https://www.hhs.gov/hipaa/for-professionals/security/hipaa-security-rule-nprm/factsheet/index.html) | What's changing, straight from the agency writing the rule |
| 4 | [Paubox: HHS pushes final Security Rule update to 2027](https://www.paubox.com/blog/hhs-pushes-final-hipaa-security-rule-update-to-2027) | Latest status and the delay to 2027 |

---

## What's changing

HHS proposed the first major update to the Security Rule since 2013 (issued December 2024, published January 2025). As of mid-2026 it is **still proposed, not law**, and final action has been pushed to at least July 2027. The current rule stays in force until then.

Among other things, the proposal would:

- Remove the "addressable" option and make nearly every specification **required**
- Require **multi-factor authentication**, with limited exceptions
- Require **encryption** of ePHI at rest and in transit
- Require a **technology asset inventory and network map**, updated at least every 12 months
- Require **vulnerability scanning** every 6 months and **penetration testing** every 12 months
- Require a **compliance audit** at least every 12 months

The MFA requirement ties straight back to the top finding in my [phishing investigation](https://github.com/atoz-guy/Cybersecurity-Technical-Portfolio/blob/main/GRC-Labs/Analysis-After-It-Happens/Lab-002-Phishing-Investigation.md).

---

## How it connects to what I know

| HIPAA Security Rule | NIST 800-53 | Where I've worked on it |
|---|---|---|
| Access control | AC-2, AC-3, AC-6 | Azure RBAC labs, CyberArk PAM track |
| Person or entity authentication | IA-2 | Entra Security Defaults lab (MFA) |
| Audit controls | AU-2 | ServiceNow SecOps |
| Security awareness training | AT-2 | Phishing investigation, Security-Awareness-Videos |
| Risk analysis | RA-3 | CRISC, my risk matrix |

*I'll confirm these mappings against the 800-66 crosswalk tables as I read it.*

---

## My notes

| Date | What I read | Key takeaway |
|---|---|---|
| | | |

---

## Planned

- [ ] Read the HHS summary
- [ ] Read NIST SP 800-66 Rev 2, focusing on the crosswalk tables and risk analysis section
- [ ] Learn the basics of HITRUST, the other framework healthcare organizations use a lot
- [ ] Build a HIPAA gap assessment of a fictional small clinic (goes in my [GRC-Labs](https://github.com/atoz-guy/Cybersecurity-Technical-Portfolio/tree/main/GRC-Labs))
