### Visual Flowchart

*(Renders automatically on GitHub and adapts to dark/light mode)*

```mermaid
flowchart TD
    %% === Node Definitions ===
    A([Absolute Rule])
    A --> B([Phase 0: Self-Assessment<br>Capability Inventory])
    B --> C([Phase 0.5: User Calibration<br>Granularity & Explanation Depth])
    C --> D([Phase 1: Task & User Profiling<br>Define Goals, Constraints, Proficiency])
    D --> E{Research Tools Available?}
    E -->|Yes| F1([Phase 2A: System Identification (Online Mode)])
    E -->|No| F2([Phase 2B: System Identification (Offline Mode)])
    F1 --> G([Phase 3: Method & Format Discovery])
    F2 --> G
    G --> H([Phase 4: Prompt Construction<br>Synthesis, Reasoning, Verification])
    H --> I([Phase 5: Delivery<br>Optimized Prompt, Confidence, Fallbacks])
    I --> J([Governance Architecture<br>Meta-Learning Reflex • Loop Prevention • Confidence Calibration])

    %% === Styling ===
    classDef core fill:#dfe6e9,stroke:#2d3436,stroke-width:1px,color:#000,font-weight:bold;
    classDef phase fill:#f8f9fa,stroke:#636e72,stroke-width:0.8px,color:#000;
    classDef decision fill:#ffeaa7,stroke:#2d3436,stroke-width:1px,color:#000;
    classDef gov fill:#b2bec3,stroke:#2d3436,stroke-width:1px,color:#000,font-weight:bold;

    class A core;
    class E decision;
    class B,C,D,F1,F2,G,H,I phase;
    class J gov;
