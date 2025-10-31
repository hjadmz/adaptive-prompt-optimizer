# Adaptive Prompt Optimizer (APO)

![License: MIT](https://img.shields.io/badge/license-MIT-blue.svg)
![Status](https://img.shields.io/badge/status-Stable-success.svg)
![Made With](https://img.shields.io/badge/made_with-Empirical_Logic-black.svg)

Meta-prompt framework for systematic AI reasoning and adaptive prompt optimization  
**Research-inspired • Self-adaptive • Future-proof • Zero-maintenance**

[Quick Start](#quick-start) • [How It Works](#how-it-works) • [Framework Structure](#framework-structure) • [Example Usage](#example-usage) • [License](#license)

---

## Overview

The **Adaptive Prompt Optimizer (APO)** is a meta-prompt framework — a single text-based protocol that transforms any conversational AI into a systematic prompt-engineering agent.

Unlike libraries or code packages, APO is **purely textual** and **architecture-agnostic**.  
It provides a reproducible reasoning protocol that enables AI systems to:

- Perform structured self-assessment  
- Adapt reasoning depth dynamically  
- Calibrate user granularity and context  
- Construct verifiable, auditable prompts  
- Deliver transparent, confidence-scored outputs  

APO draws conceptually from **cognitive science**, **systems engineering**, and **alignment strategies** common in safe AI design — distilled purely through **empirical logic** and **iterative reasoning**.

---

## Quick Start

1. **Copy** the complete meta-prompt from [`FRAMEWORK.md`](./FRAMEWORK.md).  
2. **Paste** it into any advanced AI system (e.g., ChatGPT, Claude, Gemini).  
3. **Run** it as the *system prompt* or *base instruction layer*.  
4. **Follow** the AI’s guided calibration process (Phases 0–5).

You now have a **self-adaptive reasoning engine** that tailors prompts to verified capabilities and user context.

---

## How It Works

APO functions as a **phased reasoning architecture**:

| Phase | Description |
|-------|-------------|
| **0 – Self-Assessment** | AI verifies its operational capabilities and constraints. |
| **0.5 – User Calibration** | Adjusts reasoning granularity and explanation depth. |
| **1 – Task Profiling** | Builds contextual understanding of task domain and success criteria. |
| **2 – System Identification** | Determines optimal frameworks or tools (with offline fallback). |
| **3 – Method Discovery** | Identifies or infers effective procedural methods. |
| **4 – Prompt Construction** | Synthesizes adaptive, verifiable, and structured prompts. |
| **5 – Delivery** | Outputs optimized prompt with confidence calibration and fallback guidance. |

---

## Framework Structure

### Core Flow
```
Absolute Rule  
↓  
Phase 0 → Phase 0.5 → Phase 1  
↓  
Research Tools? — Yes → Phase 2A (Online) | No → Phase 2B (Offline)  
↓  
Phase 3 → Phase 4 → Phase 5  
↓  
Governance Architecture (Meta-Learning Reflex, Loop Prevention, Confidence Calibration)
```

### Visual Flowchart

![Adaptive Prompt Optimizer Flowchart](./assets/APO_Flowchart.png)

> The flowchart visualizes APO’s full reasoning cycle — including governance oversight, adaptive branching, and refinement feedback.

---

## Conceptual Foundations

- **Cognitive Science** — Metacognition, uncertainty modeling, adaptive reasoning.  
- **Systems Engineering** — Modular verification loops, constraint feedback.  
- **AI Alignment** — Safe reasoning boundaries, corrigibility, interpretability.  

All distilled into a **self-contained textual framework** — requiring no dependencies or runtime environment.

---

## Example Usage

```text
SYSTEM:
Load Adaptive Prompt Optimizer (APO).
Run Phases 0–5 sequentially.
Apply governance and confidence calibration at each phase.
Return the final optimized prompt and reasoning summary.

APO can serve as the foundation for meta-agents, research models, or advanced reasoning tools.
```
### Visual Flowchart

*(Automatically rendered on GitHub and adapts to dark/light mode)*

```mermaid
flowchart TD
    %% ==== Core Layout ====
    style A fill:#f0f0f0,stroke:#333,stroke-width:1px,color:#000
    style G fill:#e0e0e0,stroke:#333,stroke-width:1px,color:#000

    A([Absolute Rule]):::core
    A --> B[Phase 0: Self-Assessment<br/><sub>Capability Inventory</sub>]
    B --> C[Phase 0.5: User Calibration<br/><sub>Granularity & Explanation Depth</sub>]
    C --> D[Phase 1: Task & User Profiling<br/><sub>Define Goals, Constraints, Proficiency</sub>]
    D --> E{Research Tools Available?}

    %% ==== Conditional Branch ====
    E -->|Yes| F1[Phase 2A: System Identification<br/>(Online Mode)]
    E -->|No| F2[Phase 2B: System Identification<br/>(Offline Mode)]

    %% ==== Converging Path ====
    F1 --> G[Phase 3: Method & Format Discovery]
    F2 --> G
    G --> H[Phase 4: Prompt Construction<br/><sub>Synthesis, Reasoning, Verification</sub>]
    H --> I[Phase 5: Delivery<br/><sub>Optimized Prompt, Confidence, Fallbacks</sub>]

    %% ==== Governance Layer ====
    I --> J{{Governance Architecture<br/>— Meta-Learning Reflex<br/>— Loop Prevention<br/>— Confidence Calibration}}

    %% ==== Style definitions ====
    classDef core fill:#dfe6e9,stroke:#2d3436,stroke-width:1px,color:#000,font-weight:bold
    classDef decision fill:#ffeaa7,stroke:#2d3436,stroke-width:1px,color:#000
    classDef phase fill:#f8f9fa,stroke:#636e72,stroke-width:0.8px,color:#000
    classDef gov fill:#dfe6e9,stroke:#2d3436,stroke-width:1px,font-weight:bold,color:#000

    class A core
    class E decision
    class F1,F2,B,C,D,G,H,I phase
    class J gov

---

## License

This project is licensed under the [MIT License](./LICENSE).  
© 2025–present Henry Joseph Adams. All rights reserved.
