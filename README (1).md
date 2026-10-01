# ISO 27001 Risk Assessment & Gap Analysis — NYRA (Safety Tech Startup)

Independent GRC project by **Ayesha Wasim**

## About

NYRA is a fictional early-stage startup whose app helps people stay safe in unsafe places (SOS alerts, live location sharing, unsafe-area warnings) and checks documents and messages for spam and fraud. NYRA has no formal security program yet.

This project is a full information security risk assessment and ISO/IEC 27001:2022 gap analysis for NYRA, built to practice the core work of a GRC analyst: identifying risks, scoring them, comparing the company against the Annex A control framework, and reporting findings to leadership.

## What's inside

The workbook (`ISO27001_Risk_Assessment_NYRA.xlsx`) has five tabs:

1. **Company Profile** — what NYRA does, what data it holds, its systems and vendors
2. **Risk Register** — 15 risks, each scored Likelihood (1–3) × Impact (1–3). Score 6–9 = High, 3–5 = Medium, 1–2 = Low
3. **Gap Analysis** — 17 ISO/IEC 27001:2022 Annex A controls rated Missing or Partial, each linked back to the relevant risk(s)
4. **Executive Summary** — a one-page summary for leadership with the top 5 prioritized recommendations
5. **README** — how the workbook is organized

## Key findings (summary)

- 15 risks identified across 12 categories; 8 rated High severity
- Biggest gaps: no multi-factor authentication on admin/cloud accounts, location data not encrypted at rest with no deletion policy, and no written incident response plan
- Because NYRA handles live location and emergency data, these gaps carry physical safety risk for users, not just data exposure

## Why this matters for a safety product

Most risk assessments treat a data breach as a privacy or financial problem. For NYRA, a leak of live location data could directly endanger a user. This project treats that distinction as a first-class part of the risk scoring and prioritization.

## Note

NYRA, its data, and its control statuses are fictional and created for this project. Risk scores and gap statuses reflect analyst judgment based on the scenario described in the Company Profile tab.

---
📧 ayeshawasim422@gmail.com | 🔗 [LinkedIn](https://www.linkedin.com/in/ayesha-wasim-a4275b296)
