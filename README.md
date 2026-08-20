# Sales & Revenue AI Automation System

**An AI-driven lead qualification and revenue system that scaled a 4-person pilot into a $15M+ annual PPL engine — built and led at Gartner Digital Markets.**

![Type: Revenue AI](https://img.shields.io/badge/Type-Revenue%20AI-1F3864) 
![Domain: Sales Enablement](https://img.shields.io/badge/Domain-Sales%20Enablement-1F3864) 
![Status: Production](https://img.shields.io/badge/Status-Production-2E7D32)

---

## Overview

Gartner Digital Markets' India prospecting operation started as a self-funded experiment: four interns manually qualifying leads for the software review platform's catalogue. I architected and led the AI-driven revenue system that scaled that experiment into a dedicated team generating **USD 15M+ in annual PPL revenue** and **USD 2M+ in PPC revenue** — without proportional headcount growth.

The system's core insight: stop optimising for lead volume. Optimise for revenue per lead by combining firmographic enrichment, behavioral signals, and intelligent routing to get high-intent leads to the right sales rep at the right time.

---

## Impact

| Metric | Result |
|---|---|
| PPL revenue generated | **USD 15M+ annually** |
| PPC revenue | **USD 2M+ annually** |
| Cost Per Lead reduction | **25%** across Asian and European markets |
| New vendors onboarded monthly | **~2,500** |
| Territory coverage expansion | **10–15%** |

---

## System Architecture

```mermaid
flowchart TD
    A[Lead Sources] --> B[Data Enrichment Layer<br/>firmographic + behavioral signals]
    B --> C[Segmentation Engine<br/>geography, product, intent signals]
    C --> D[Lead Scoring Model]
    D --> E{Decision Engine}
    E -->|High Intent| F[Sales Team — direct routing]
    E -->|Medium Intent| G[Nurture Funnel]
    E -->|Low Intent| H[Filtered Out]
    F --> I[CRM & Tracking]
    G --> I
    I --> J[Revenue Tracking]
    J --> K[Feedback Loop]
    K --> C
```

---

## How It Works

**Data Enrichment Layer** — every inbound lead is enriched with firmographic data (company size, sector, geography) and behavioral signals before any human sees it.

**Segmentation Engine** — leads are grouped by territory, product category, and intent tier to enable targeted rather than spray-and-pray outreach.

**Lead Scoring Model** — a scoring algorithm ranks leads by conversion likelihood, feeding the decision engine.

**Decision Engine** — routes high-intent leads directly to sales reps, medium-intent leads into a nurture funnel, and low-quality leads out of the pipeline entirely.

**Feedback Loop** — conversion and revenue data feeds back into the segmentation and scoring model continuously.

---

## My Role

I conceived, architected, and led the build of this system — from the original 4-intern pilot to the full production revenue engine. I defined the lead scoring logic, the segmentation approach, and the routing criteria, and partnered with engineering to ship it into production.

---

## Related

This revenue system is part of a unified AI architecture across Trust & Safety and Revenue operations.  
👉 [Full case study: AI Revenue Case Study](https://github.com/vickybansal99-tech/ai-revenue-case-study)

---

*Enterprise-grade systems built within global marketplace operations. Specific tooling and data sources are generalised due to confidentiality.*
