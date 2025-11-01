<p align="center">
  <!-- Hero banner (glass). Provide both modes. -->
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./assets/hero-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="./assets/hero-light.svg">
    <img src="./assets/hero-light.svg" width="100%" alt="Adaptive Prompt Optimizer">
  </picture>
</p>

> [!IMPORTANT]
> **APO is a protocol — not software.** Any model can execute it entirely through text.

<p align="center">
  <a href="./LICENSE">
    <img src="https://img.shields.io/badge/license-MIT-1f2937?labelColor=0b1020&logo=opensourceinitiative&logoColor=white" alt="MIT License">
  </a>
  <img src="https://img.shields.io/badge/type-meta--prompt-312e81?labelColor=0b1020" alt="Meta-Prompt">
  <img src="https://img.shields.io/badge/status-stable-065f46?labelColor=0b1020" alt="Stable">
</p>

## Overview

**Adaptive Prompt Optimizer (APO)** is a universal meta‑prompt framework that turns any conversational AI into a self‑adaptive reasoning system—capable of structured self‑assessment, confidence calibration, and transparent prompt generation.

- **Text‑only** — Works in any AI chat or reasoning model  
- **Model‑agnostic** — Compatible with ChatGPT, Claude, Gemini, and future systems  
- **Zero‑maintenance** — No code or dependencies to update  
- **Future‑proof** — Designed to remain valid across AI generations

> [!TIP]
> Use APO as a **system prompt** or **instruction layer**. This is the simplest, most reliable integration path.

## Quick start

1. Open [`FRAMEWORK.md`](./FRAMEWORK.md)  
2. Copy the complete meta‑prompt  
3. Paste into your AI system (ChatGPT, Claude, Gemini, etc.)  
4. Run as a **system prompt** or **instruction layer**  
5. Follow the guided calibration

<!-- Optional demo media: add later if desired -->
<!--
<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./assets/demo-dark.gif">
    <source media="(prefers-color-scheme: light)" srcset="./assets/demo-light.gif">
    <img src="./assets/demo-light.gif" width="860" alt="APO demo">
  </picture>
</p>
-->

## Architecture

APO follows a six‑phase adaptive reasoning cycle inspired by metacognition and control theory.

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./assets/diagram-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="./assets/diagram-light.svg">
    <img src="./assets/diagram-light.svg" width="100%" alt="Six-Phase Reasoning Cycle">
  </picture>
</p>

| Phase | Function |
|:--|:--|
| **0 – Self‑Assessment** | Verify model capabilities and constraints |
| **0.5 – User Calibration** | Match depth and tone to user preference |
| **1 – Task Profiling** | Define goals, success criteria, and context |
| **2 – System Identification** | Map tools or research access |
| **3 – Method Discovery** | Select optimal reasoning strategy |
| **4 – Prompt Assembly & Delivery** | Generate and validate the adaptive prompt |

## Core principles

- **Absolute rule** — Never fabricate or assume; disclose uncertainty with alternatives.  
- **Self‑assessment** — Establish operational boundaries before reasoning.  
- **Calibration** — Adapt depth and style to the user and the model.  
- **Verification** — Include rationale, evidence, and confidence indicators.  
- **Governance** — Embed loop‑prevention and reflexive checks.

## Future‑proof by design

> [!NOTE]
> APO is a **stable reference** protocol. Edits to the text may impact reliability. Forks for derivatives are welcome.

- Protocol, not software: text survives platform and model shifts  
- No planned updates: issues/PRs are disabled by design  
- Designed to be used, cited, and replicated without maintenance

## Media placeholders

Place media in `assets/` using these names so the README switches automatically between light and dark mode.

- Hero banners (required)  
  - `assets/hero-dark.svg`  
  - `assets/hero-light.svg`  

- Architecture diagram (required)  
  - `assets/diagram-dark.svg`  
  - `assets/diagram-light.svg`  

- Optional demo GIF  
  - `assets/demo-dark.gif`  
  - `assets/demo-light.gif`  
  - Guidance: 10–12 seconds, muted capture, 800–1200px wide, < 5MB

> [!TIP]
> If an asset is neutral (works in both modes), reference the single file directly without `<picture>`.

## Repository structure

