# 🤖 AI Prompt: Leading or Experiencing Termination with Legal Clarity and Emotional Intelligence

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](./LICENSE)
[![EI Focused](https://img.shields.io/badge/Emotional_Intelligence-Enabled-blueviolet)](https://www.linkedin.com/in/emcdo411)
[![HR Ready](https://img.shields.io/badge/HR--Approved-✅-success)](https://www.shrm.org/)
[![Prompt Quality](https://img.shields.io/badge/Prompt-Tested-brightgreen)](https://www.chat.openai.com)
[![Feedback Welcome](https://img.shields.io/badge/Feedback-Welcome-yellow)](https://linkedin.com/in/emcdo411)

A best-in-class AI prompt to guide HR leaders, People Ops managers, and emotionally intelligent executives through one of the most sensitive and consequential moments in modern work: **letting someone go — or being let go — with both legal clarity and human dignity**.

---

## 📌 Table of Contents

1. [Overview](#1-overview)  
2. [Why This Prompt Matters](#2-why-this-prompt-matters)  
3. [What the Prompt Covers](#3-what-the-prompt-covers)  
4. [Mermaid Workflow: Termination with EI + Legal Care](#4-mermaid-workflow-termination-with-ei--legal-care)  
5. [Mermaid Diagram: Hiring Process Overview](#5-mermaid-diagram-hiring-process-overview)  
6. [Live Prompt Box](#6-live-prompt-box)  
7. [Suggested Use Cases](#7-suggested-use-cases)  
8. [Feedback Request](#8-feedback-request)  
9. [Sources & Statistics](#9-sources--statistics)  

---

## 1. Overview

This AI-engineered prompt is designed to simulate real-world termination or layoff experiences from either the manager's or employee's perspective. It offers a grounded, legally responsible, and emotionally intelligent response for navigating these difficult transitions.

---

## 2. Why This Prompt Matters

While layoffs and terminations are often seen as procedural, they leave a lasting imprint on individual careers, company cultures, and public reputations.

> 🔹 In June 2025, the Bureau of Labor Statistics reported **5.3 million separations** in the U.S. labor force.  
> 🔹 A 2024 LinkedIn Workplace Learning Report cited **Emotional Intelligence as a top 5 skill in demand by 2030**, especially for People Managers.  
> 🔹 According to McKinsey (2023), companies that prioritize “employee dignity during separation” see **22% higher rehire rates and 31% lower internal attrition**.

---

## 3. What the Prompt Covers

- ✅ Pre-termination legal and HR checklist  
- ✅ Tone-sensitive scripts for managers  
- ✅ Regional compliance nuances (U.S., UK, EU, remote/global)  
- ✅ Respectful and empowering reframes for employees  
- ✅ DEI risk checks and post-event morale support  
- ✅ Formatting options for coaching, PDF, and slide deck output  

---

## 4. Mermaid Workflow: Termination with EI + Legal Care

> A visual representation of the decision and communication flow using Emotional Intelligence and compliance logic.

```mermaid
graph TD
  %% =========================
  %% SWIMLANES (SUBGRAPHS)
  %% =========================
  subgraph L1[Legal & Compliance]
    LSTART[Gate: Termination Request Received]
    LTYPE{Type Check<br/>Layoff or Performance}
    LREG{Region Check<br/>US EU UK APAC}
    LWC[Works Council or Consultation<br/>as required]
    LADV[Adverse Impact Review]
    LAUD[Audit Pack Ready]
  end

  subgraph L2[HR / People]
    HUP[Prechecks<br/>PIP in place if performance<br/>Docs quality verified]
    HPROT[Protected Status or Leave Check<br/>eg medical parental]
    HVISA[Immigration or Visa Review]
    HPACK[Prepare Package<br/>Severance benefits outplacement]
    HMEET[Schedule Private Meeting<br/>HR present manager briefed]
    HAFTER[Aftercare Touchpoints<br/>24h 7d 30d follow ups]
    HFILE[Record & Retention<br/>File in HRIS]
  end

  subgraph L3[Manager]
    MBRIEF[Manager Prebrief<br/>script practice EI coaching]
    MDELIVER{Deliver News<br/>with empathy and clarity}
    MDEC[If new facts emerge<br/>request exception or appeal]
    MTRAIN[Manager Enablement<br/>post event coaching]
  end

  subgraph L4[IT / Security]
    ITPLAN[Offboarding Plan<br/>apps access devices]
    ITCUT[Access Disablement<br/>at meeting time]
    ITREC[Device Retrieval & Data Return]
  end

  subgraph L5[Finance / Payroll]
    FPAY[Final Pay Calculation<br/>salary PTO commission]
    FBEN[Benefits & Coverage<br/>COBRA or local equivalent]
    FEQ[Equity or Bonus Treatment<br/>per policy]
  end

  subgraph L6[Communications]
    COMMS[Comms Kit<br/>manager script FAQ timing]
    TEAMMSG[Team Message Sequencing<br/>impacted then remaining]
  end

  subgraph L7[Metrics & Learning]
    METRICS[Capture KPIs<br/>cycle time errors sentiment]
    IMPROVE[Policy & Training Updates]
  end

  %% =========================
  %% CONTEXT BANNERS (OPTIONAL)
  %% =========================
  RISK[Context<br/>Market reductions and automation risk]
  CAREERS[Context<br/>Reemployment and outplacement resources]

  %% =========================
  %% MAIN FLOW
  %% =========================
  LSTART --> LTYPE
  LTYPE -->|Layoff| LREG
  LTYPE -->|Performance| HUP

  %% Layoff path
  LREG --> LWC
  LWC --> LADV
  LADV --> HPACK

  %% Performance path guardrails
  HUP --> HPROT --> HVISA --> LADV --> HPACK

  %% Cross functional preparation
  HPACK --> HMEET
  HPACK --> FPAY
  HPACK --> FBEN
  HPACK --> FEQ
  HPACK --> COMMS
  COMMS --> TEAMMSG

  %% IT planned in parallel
  HPACK --> ITPLAN
  ITPLAN --> ITCUT
  ITCUT --> ITREC

  %% Manager enablement and delivery
  HMEET --> MBRIEF --> MDELIVER

  %% Meeting outcomes
  MDELIVER --> HAFTER
  MDELIVER --> ITCUT
  MDELIVER --> FPAY
  MDELIVER --> FBEN
  MDELIVER --> FEQ

  %% Documentation and audit
  HAFTER --> HFILE --> LAUD

  %% Appeals or exceptions
  MDELIVER -->|New facts| MDEC -->|Approve| HPACK
  MDEC -->|Deny| HAFTER

  %% Post event manager support
  HAFTER --> MTRAIN

  %% Metrics & learning loop
  LAUD --> METRICS --> IMPROVE
  IMPROVE --> HUP
  IMPROVE --> COMMS
  IMPROVE --> ITPLAN
  IMPROVE --> FPAY

  %% Context links (dotted)
  LTYPE -. context .-> RISK
  HAFTER -. resources .-> CAREERS

  %% =========================
  %% STYLES
  %% =========================
  classDef legal fill:#0d6efd,stroke:#153a72,color:#fff,stroke-width:2px;
  classDef hr fill:#3aa0ff,stroke:#153a72,color:#fff,stroke-width:2px;
  classDef mgr fill:#6c757d,stroke:#1a3c6e,color:#fff,stroke-width:2px;
  classDef it fill:#0b7285,stroke:#093b44,color:#fff,stroke-width:2px;
  classDef fin fill:#1f8b4c,stroke:#0f4a28,color:#fff,stroke-width:2px;
  classDef comms fill:#8e44ad,stroke:#4a235a,color:#fff,stroke-width:2px;
  classDef learn fill:#e67e22,stroke:#7e3f0e,color:#fff,stroke-width:2px;
  classDef banner fill:#2b2b2b,stroke:#555,color:#eaeaea,stroke-width:1.5px;

  class LSTART,LTYPE,LREG,LWC,LADV,LAUD legal;
  class HUP,HPROT,HVISA,HPACK,HMEET,HAFTER,HFILE hr;
  class MBRIEF,MDELIVER,MDEC,MTRAIN mgr;
  class ITPLAN,ITCUT,ITREC it;
  class FPAY,FBEN,FEQ fin;
  class COMMS,TEAMMSG comms;
  class METRICS,IMPROVE learn;
  class RISK,CAREERS banner;

````

---

## 5. Mermaid Diagram: Hiring Process Overview

```mermaid
sequenceDiagram
    actor Candidate
    participant HR
    participant Manager
    Candidate->>HR: Submit Application
    HR->>Manager: Review Application
    Manager->>Candidate: Schedule Interview
    Candidate->>Manager: Complete Interview
    Manager->>HR: Approve Candidate
    HR->>Candidate: Send Offer
    Candidate->>HR: Accept Offer
    HR->>Candidate: Onboard
```

---

## 6. Live Prompt Box

👉 Click here to [copy the full AI prompt for your HR tool](./termination_prompt.md)

You can also use it with ChatGPT, Claude, or your in-house LLM for simulation and coaching.

---

## 7. Suggested Use Cases

* 🔹 Manager training modules
* 🔹 Executive coaching frameworks
* 🔹 HR policy onboarding
* 🔹 DEI-sensitive layoffs or reorg planning
* 🔹 Talent and culture preservation planning during RIFs

---

## 8. Feedback Request

> 🧠 **HR Professionals & DEI Leaders** — I’m actively seeking feedback on this prompt.
> What’s helpful? What would you change?
> Drop a GitHub issue or leave a comment on my [LinkedIn post](https://linkedin.com/in/emcdo411)
> Your input helps refine this as a living, open-source HR tool.

---

## 9. Sources & Statistics

* [U.S. Bureau of Labor Statistics — Job Openings and Labor Turnover, June 2025](https://www.bls.gov/news.release/jolts.nr0.htm)
* [McKinsey & Company — Rehumanizing Layoffs (2023)](https://www.mckinsey.com/capabilities/people-and-organizational-performance/our-insights/how-to-rehumanize-layoffs)
* [LinkedIn Learning Workplace Skills Report (2024)](https://learning.linkedin.com/resources/workplace-learning-report)
* [Society for Human Resource Management (SHRM) — Employee Separation Guidelines](https://www.shrm.org/resourcesandtools/tools-and-samples/hr-qa/pages/terminations.aspx)

---

### 🧠 Built and maintained by: [Erwin Maurice McDonald](https://github.com/emcdo411)

📬 Reach out if you'd like a version tailored to your org or team.

```

Let me know if you’d like this saved as a `.md` file or if you’re ready for the LinkedIn post copy to promote it.
```


