# GRC Learning Pathway

**Goal:** ServiceNow GRC, SecOps and IRM Implementation and Technical Architect

How I'm building toward a GRC role. Microsoft and cloud cover the technical controls, ServiceNow handles governance and compliance workflow, and ISACA gives me the audit and risk foundation.

---

## How I see it

**GRC Playground is the bubble.** It shows how GRC can control things, how it's used, and how much reach it has. Anyone looking at it can understand what GRC does and what it can do.

**ServiceNow is the platform that makes it real.** Most companies already run on it, at least for ticketing, and many use it for much more. I haven't found anything else that covers GRC as completely.

**ISACA ties it all together.** CRISC, CISM, CISA and CGEIT help me understand how the pieces fit. Most of all, they show people what I'm capable of before they've even met me.

**Every other tool feeds the bubble.** Before I add a tool, I ask: which control does it help me enforce or prove? If it doesn't strengthen a control, it can wait.

### An example

Without ISACA, I'm the tech who shows up with a problem. With ISACA, the CISO sees that I understand their job: risk, budget, accountability. So when I bring them a ticket, they're ready to listen.

Then GRC Playground and ServiceNow give me the technical side, and I can explain it in plain words:

- **What's happening:** the risk, in business terms
- **What I can do:** the control that fixes it
- **How I'll hand it off:** tracked in ServiceNow, with owners and proof it's done

That's the forward deployed role as a cybersecurity specialist: the person who speaks both languages, leadership and technical, and connects them.

```
                    GRC Playground
            (the bubble: what GRC can control)
                          │
      ┌───────────┬───────┴────────┬──────────────┐
      │           │                │              │
   CyberArk     Okta /          ServiceNow     Python
  privileged    Entra          workflow and   risk scoring
   access       identity       audit evidence  and automation
```

---

## Where I am now

**Done**
- ServiceNow: CSA, CIS-RC, and SecOps (CIS-DF, then CIS-SIR and CIS-VR)
- Microsoft: SC-100, SC-300, SC-401, AZ-104, PL-300
- CompTIA: Security+, Linux+, SecAI+
- AWS SAA-C03, LPIC-1
- Python: PCEP, PCAP, PCPP1
- Google: Cybersecurity, IT Support, IT Automation with Python, Data Analytics
- ISACA CRISC exam

**Now**
- December 2026: next ISACA exam, either CISM or CISA
- CISM is definitely on the list. CISA is likely too, since passing it before I have the work experience still earns the Associate title.
- Building hands-on ServiceNow projects to go with the certs

**Next year**
- GRC Playground labs: the center of everything else
- ServiceNow PDI builds, then CAD (Certified Application Developer) and CTA (Certified Technical Architect)
- CyberArk labs and exam: privileged access control
- Okta: identity control, after CyberArk
- ISACA CGEIT

**Optional: if job postings ask for it**
- Archer Certified Associate (Level 1): Archer is ServiceNow's main GRC platform competitor. The exam is open book, 70 questions in 90 minutes, 70% to pass, $100, with one retake within 60 days. You can't open Archer's training courses during the exam, so save notes or PDFs beforehand. ([Archer exam tips](https://community.archerirm.com/hc/en-us/articles/52147200637075-Archer-Platform-Certification-Preparation-Tips))

**About two years out**
- CompTIA CySA+: the next step up from Security+, and passing it renews Security+ too
- LPIC-2: deeper Linux, which matters for auditing how servers are hardened and logged

---

## How I approach GRC

1. **Learn one framework at a time.** NIST CSF first, then ISO 27001, then SOC 2.
2. **Do it on something real.** Use my own business as the environment for gap analysis and risk assessments, as if I were auditing it for a client.
3. **Track the work like tickets.** Every assessment or finding gets documented here so the work is visible.
4. **Connect the layers.** For each control, write down:
   - What the requirement is
   - Which technical setting enforces it (Entra, M365, Azure, CyberArk)
   - Where the evidence comes from and whether it can be collected automatically
   - How it's tracked in ServiceNow IRM

---

## ServiceNow IRM focus areas

- **Policy and Compliance:** mapping regulations like NIST and ISO to controls
- **Risk Management:** risk registers, assessments, issue tracking
- **Security Operations:** linking security tools to incident and vulnerability workflows
- **CMDB:** knowing what assets exist, since you can't govern what you can't see

---

## Threat modeling

| Method | When to use it | Question it answers |
|---|---|---|
| STRIDE | Reviewing one system, feature or API | Can this be spoofed, tampered with or abused? |
| PASTA | Presenting risk to management | How would this threat affect the business? |

Resources I'm using:
- Performing Threat Modeling with the PASTA Methodology
- Infosec Institute Threat Modeling learning path (includes data flow diagram labs)

---

## Business side of risk

Part of GRC is explaining risk in terms of cost. I'm reading up on risk quantification and total cost of ownership so I can say what a control saves, not just that it's required.
