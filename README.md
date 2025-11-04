<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./assets/logo-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="./assets/logo-light.svg">
    <img src="./assets/logo-light.svg" alt="Adaptive Prompt Optimizer" width="420">
  </picture>
</p>

<p align="center">
  <b>A model-agnostic meta-prompt protocol for structured AI reasoning and self-assessment.</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/License-MIT-3B82F6?style=flat-square&labelColor=1E293B&logo=open-source-initiative&logoColor=white" alt="MIT License" height="22">
  <img src="https://img.shields.io/badge/Type-Protocol-4338CA?style=flat-square&labelColor=1E293B" alt="Protocol" height="22">
  <img src="https://img.shields.io/badge/Maintenance-Zero-64748B?style=flat-square&labelColor=1E293B" alt="Zero Maintenance" height="22">
</p>

<hr/>

## Overview

**Adaptive Prompt Optimizer (APO)** is a universal, text-only meta-prompt framework—model-agnostic, self-calibrating, and future-proof. It standardizes structured reasoning, confidence reporting, and governance **without code**, so any AI model can execute it via text.

**Why APO**
- **Text-only**: works in any AI chat or reasoning model  
- **Model-agnostic**: usable across vendors and architectures  
- **Zero-maintenance**: intentionally static; no updates or dependencies  
- **Auditable**: explicit phases, confidence, and safeguards

> **Protocol, not software.** This repository is complete and archived by design. Forks are welcome for customization.

## Quick Start

1. Open **[FRAMEWORK.md](./FRAMEWORK.md)**  
2. Copy the complete meta-prompt  
3. Paste into your AI system (ChatGPT, Claude, Gemini, etc.)  
4. Run as a **system prompt** or **instruction layer**  
5. Follow the guided calibration

## Architecture

APO follows a six-phase adaptive reasoning cycle.

<p align="center">
  <img src="assets/diagram-light.svg#gh-light-mode-only" width="85%" alt="APO Reasoning Phases – Light Mode">
  <img src="assets/diagram-dark.svg#gh-dark-mode-only" width="85%" alt="APO Reasoning Phases – Dark Mode">
</p>

| **Phase** | **Function** |
|-----------|--------------|
| 0 – Self-Assessment | Verify capabilities and constraints |
| 0.5 – User Calibration | Match depth and tone to user preference |
| 1 – Task Profiling | Define goals, success criteria, and context |
| 2 – System Identification | Map tools and knowledge access |
| 3 – Method Discovery | Select optimal reasoning strategy |
| 4 – Prompt Construction | Validate and deliver the adaptive prompt |

## Features

- **Self-Assessment** — model probes its own capabilities first  
- **User Calibration** — adapts depth, tone, and format  
- **Confidence Reporting** — quantifies uncertainty explicitly  
- **Research Integration** — uses tools when available  
- **Loop Prevention** — governance to avoid recursion  
- **Temporal Awareness** — separates timeless vs. time-sensitive data

## Core Principles

- **Absolute rule** — never fabricate; disclose uncertainty with alternatives  
- **Verification** — rationale, evidence, and confidence indicators  
- **Calibration** — align with the user and the model's constraints  
- **Governance** — reflexive checks and anti-loop safeguards  
- **Simplicity** — optimize for the user's actual context, not hypotheticals

## Usage & Adaptation

Provided **as-is** under MIT. You may:
- Use APO in any AI system
- Fork and adapt for your own workflows
- Study the methodology and architecture
- Build derivative frameworks

This protocol is intentionally **static** to ensure long-term stability and reliability.

## License

Distributed under the [MIT License](./LICENSE). © 2025 Henry Joseph Adams

## Citation

If you reference APO in research or documentation, please cite. See **[CITATION.cff](./CITATION.cff)**.
  
<p align="center"><sub>Complete • Future-proof • No maintenance intended</sub></p>
