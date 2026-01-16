# AI_RMF
Mirror for NIST AI-100 and NIST AI RMF
This repository contains three artifacts:

NIST.AI.100‑1.pdf — Official NIST AI Risk Management Framework
AI_RMF_Playbook.pdf — NIST’s operational guidance companion to the RMF
nist_ai_rmf_playbook.csv — Structured extraction of MANAGE‑function guidance from the Playbook

Below is a tight table‑of‑contents summary for each, plus how an agent should use them.

1. NIST.AI.100‑1.pdf — AI Risk Management Framework (RMF 1.0)
(Full authoritative framework — structure extracted directly from the PDF TOC)
 [NIST.AI.100-1.pdf | PDF]
Executive Summary
Part 1 — Foundational Information

Framing Risk
▪ Risk, Impacts, Harms
▪ Risk Measurement, Tolerance, Prioritization, Organizational Integration
Audience
AI Risks & Trustworthiness
▪ Valid & Reliable
▪ Safe
▪ Secure & Resilient
▪ Accountable & Transparent
▪ Explainable & Interpretable
▪ Privacy‑Enhanced
▪ Fairness / Harmful Bias
Effectiveness of the AI RMF

Part 2 — Core & Profiles

AI RMF Core
Functions: GOVERN → MAP → MEASURE → MANAGE
AI RMF Profiles
▪ Use‑case profiles
▪ Temporal profiles (current/target)

Appendices
A. AI Actor Tasks
B. AI Risks vs Traditional Software Risks
C. Human–AI Interaction Considerations
D. RMF Design Attributes

2. AI_RMF_Playbook.pdf — Operational Companion to the RMF
(Note: You did not request extraction for this one; no PDF was fetched. Summaries instead come from patterns in the CSV + context from NIST.)
Playbook Structure (High‑level)
The Playbook mirrors the four RMF functions but provides tactical actions, questions, and procedural guidance.
Sections


GOVERN Playbook
▪ Organizational policies
▪ Roles & responsibilities
▪ Accountability structures
▪ Diversity / human factors integration
▪ Third‑party / supply‑chain considerations


MAP Playbook
▪ Context establishment
▪ System categorization
▪ Impact characterization
▪ TEVV planning for context
▪ Human oversight design


MEASURE Playbook
▪ Risk metrics selection
▪ TEVV execution
▪ Trustworthiness characteristic measurement
▪ Bias, privacy, safety, security testing
▪ Drift & emergent risk tracking


MANAGE Playbook
▪ Risk treatment / response
▪ Incident response & communication plans
▪ Residual risk disclosure
▪ System decommissioning
▪ Change management and continuous improvement


The CSV file below gives more detail for MANAGE.

3. nist_ai_rmf_playbook.csv — Extracted MANAGE‑Function Guidance
(Structured text pulled directly from CSV parsing)
 [nist_ai_rm...aybook.csv | Excel]
This CSV appears to capture:
MANAGE Subcategories with Playbook Guidance


MANAGE 1.x — Prioritization & Risk Treatment
▪ Decide whether to proceed with system development
▪ Prioritize treatments
▪ Document residual risks
▪ Examine tradeoffs using interdisciplinary input


MANAGE 2.x — Maximizing Benefits / Minimizing Impacts
▪ Consider alternative approaches
▪ Monitor drift and degradation
▪ Respond to unknown risks
▪ Deactivate/decommission when necessary


MANAGE 3.x — Third‑Party / Pre‑Trained Model Risk
▪ Monitor third‑party models
▪ Require documentation
▪ Establish contingency processes
▪ Track vulnerabilities


MANAGE 4.x — Monitoring, Feedback, and Continuous Improvement
▪ Continuous monitoring
▪ Red‑teaming
▪ Incident documentation
▪ Root‑cause analysis
▪ Stakeholder disclosure
▪ Versioning & change history


The CSV also contains extensive appended references, transparency questions, and risk‑management checklists.

🧠 How an Agent Should Use These Three Files
1. Use NIST.AI.100‑1.pdf for:

Definitions, vocabulary, and canonical structure
All top‑level questions about what the RMF is
How the four functions relate & what outcomes define “compliance”

If an agent must classify, reason, or map a task to NIST RMF, this is the ground truth.

2. Use AI_RMF_Playbook.pdf for:

Actionable steps
Checklists and procedural recommendations
Templates for: governance, metrics, oversight, decommissioning, documentation
“How do I implement this RMF requirement?” tasks

This is the operations manual.

3. Use nist_ai_rmf_playbook.csv for:

Fast retrieval of MANAGE‑function tasks
Extracting risk‑treatment patterns
Programmatically referencing guidance for automation or scoring

This file is the quickest way for an agent to reason about post‑deployment risk management.

🔧 Recommended Agent Behaviors
When given any user task/problem:

Classify it under GOVERN / MAP / MEASURE / MANAGE
Pull relevant structured details:
- RMF definitions → PDF
- Playbook actions → Playbook
- MANAGE guidance → CSV
Ask clarifying questions only when necessary for context, not for internal structure.
Output recommended actions mapped to RMF categories/subcategories.
If assessing AI system behavior, auto‑check for:
▪ Trustworthiness characteristics
▪ Required documentation
▪ Required TEVV steps
▪ Residual risk
▪ Required human oversight design
