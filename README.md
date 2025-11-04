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
  <img src="https://img.shields.io/badge/Type-Meta--Protocol-4338CA?style=flat-square&labelColor=1E293B" alt="Meta-Protocol" height="22">
  <img src="https://img.shields.io/badge/Maintenance-Zero-64748B?style=flat-square&labelColor=1E293B" alt="Zero Maintenance" height="22">
</p>

<hr/>

## Overview

**Adaptive Prompt Optimizer (APO)** is a universal, text-only meta-prompt protocol—model-agnostic, self-calibrating, and future-proof. It enables any AI to reason with structure, assess its own limits, and deliver auditable output by recursively generating and refining reasoning instructions.

**Why APO**
- **Text-only**: works in any AI chat or reasoning model
- **Model-agnostic**: compatible with different vendors and architectures
- **Meta-prompt architecture**: generates and calibrates its own reasoning structure
- **Zero-maintenance**: intentionally static, no updates ever required—future-proof by design

> [!IMPORTANT]
> **APO is a meta-prompt protocol—not software.** It teaches AI systems to optimize their own reasoning processes. This is a complete, archived framework. Users are encouraged to fork and adapt for specific needs.

## Quick Start

1. Open **[FRAMEWORK.md](./FRAMEWORK.md)**
2. Copy the complete meta-prompt
3. Paste into your AI system (ChatGPT, Claude, Gemini, etc.)
4. Run as a **system prompt** or **instruction layer**
5. Follow the guided calibration

## Architecture

APO follows a six-phase adaptive reasoning cycle, where each phase recursively optimizes the structure and strategy of the AI's response.

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

- **Self-Assessment** — Model probes its own capabilities and boundaries before reasoning
- **Recursive Calibration** — Adapts reasoning depth, tone, and structure based on user and context
- **Confidence Quantification** — Explicit uncertainty reporting with fallback strategies
- **Tool Integration** — Leverages research tools when available; operates offline when needed
- **Governance & Loop Prevention** — Built-in reflexive checks and anti-recursion safeguards
- **Temporal Abstraction** — Separates timeless reasoning principles from time-sensitive data

## Core Principles

- **Absolute rule** — Never fabricate; always disclose uncertainty with alternative pathways
- **Structural self-awareness** — Establish operational boundaries before generating reasoning
- **Calibration-first** — Align reasoning depth, tone, and methodology to the user and model constraints
- **Verification & rationale** — Include evidence, reasoning steps, and explicit confidence indicators
- **Governance & reflexion** — Recursive checks prevent loops and enforce safety constraints

## Usage & Adaptation

Provided **as-is** under MIT. You may:
- Use APO directly in any AI system
- Fork and adapt for your own workflows
- Study the methodology and meta-architecture
- Build derivative meta-prompt frameworks

This protocol is intentionally **static** to ensure long-term stability and remain **universally future-proof**.

## License

Distributed under the [MIT License](./LICENSE). © 2025 Henry Joseph Adams

## Citation

If you reference APO in research or documentation, please cite. See **[CITATION.cff](./CITATION.cff)**.

<p align="center"><sub>Complete Protocol • Meta-Prompt Architecture • Intentionally Static • Future-Proof</sub></p>
