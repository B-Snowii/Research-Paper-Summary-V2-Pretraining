[![Language](https://img.shields.io/badge/Language-English-blue)](README.md)
[![语言](https://img.shields.io/badge/语言-中文-red)](README.zh-CN.md)

# Academic Paper Summary · V2 Pretraining

This repository showcases a workflow and key implementation for generating professional around 25-word summaries for academic papers, built for a research institute.

- Task: Produce around 25-word academic summaries for many papers weekly, used in weekly Research alerts.
- Key Outcomes:
  - Time cost: Before over 40 hrs/week → After ≤ 2 hrs/week
  - Quality assurance: Method/topic accuracy and consistent style
  - Reusability: MCP pipeline + edits data
- Background & Goals:
  - Time constraint: Summaries finalized within 4 days due to time sensitivity.
- Practical Challenges:
  - High volume and urgency
  - Broad topics and methods; high comprehension cost
  - Repeated internal edits and communication

## Version Rationale (V2 · Pretraining)
- Why this attempt: Inject domain knowledge via pretraining to improve method/topic fidelity; explore weight‑init scaling.
- Why we moved on: Domain‑fit corpus curation is costly and hard to cover all topics; working papers’ novelty → scarce similar materials → low ROI.

## Links
- Main repo: https://github.com/B-Snowii/Research-Paper-Summary-Collection
- License: MIT
