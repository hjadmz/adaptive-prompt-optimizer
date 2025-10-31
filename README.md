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
