---

## Client Intake & Deal Qualification System (Mock)

A structured client intake and deal qualification system designed for a small automation consultancy to assess inbound leads, prioritise opportunities, and reduce time spent on low-quality prospects.

The system:
- Captures structured lead intake data across company, use case, and trigger context
- Assesses commercial fit using weighted scoring and risk modifiers
- Supports consistent go / nurture / disqualify decisions
- Creates a repeatable qualification process independent of individual judgement

This case study documents the design of a structured client intake and deal qualification system for a small automation consultancy operating in a mixed inbound and referral-led sales environment. The business faced increasing volume and variability in incoming opportunities, with leads differing significantly in urgency, commercial value, delivery complexity, and data sensitivity. Prior to this system, qualification decisions were made using informal judgement, scattered notes, and inconsistent criteria, resulting in time spent on low-quality opportunities and limited visibility into why certain leads were progressed, deprioritised, or rejected.

The solution introduces a two-stage qualification framework combining a structured intake tracker with a weighted scoring model to support consistent, repeatable decision-making. Lead context, triggers, operational pain points, and current processes are captured upfront, then assessed against defined criteria including use-case fit, authority access, budget alignment, urgency, delivery complexity, and data or security risk. The scoring model produces clear decision outputs (progress, nurture, or disqualify), supported by documented rationale and review notes. Although implemented using lightweight tools for accessibility, the system mirrors enterprise CRM qualification logic and is designed to be directly transferable into platforms such as Salesforce, enabling scalable adoption as the business grows.

### Client Intake Tracker – Overview (Mock)

High-level view of inbound leads, including company context, use case summary, trigger for engagement, current process, and expected impact if no change is made.

![Client Intake Tracker Overview](./screenshots/intake-tracker-overview.png)

*This view enables quick assessment of lead context and surfaces operational pain points before moving into qualification.*

### Qualification Scoring & Decision Model (Mock)

A weighted scoring model used to assess deal viability based on need clarity, use-case fit, authority access, budget, urgency, delivery complexity, and data risk.

![Qualification Scoring Overview](./screenshots/qualification-scoring-overview.png)

*This model supports objective prioritisation and reduces time spent on low-probability opportunities while preserving higher-upside leads for nurturing.*
