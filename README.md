### Visual Flowchart

```mermaid
flowchart TD
    A[Absolute Rule]
    A --> B[Phase 0: Self-Assessment\nCapability Inventory]
    B --> C[Phase 0.5: User Calibration\nGranularity & Explanation Depth]
    C --> D[Phase 1: Task & User Profiling\nGoals, Constraints, Proficiency]
    D --> E{Research Tools Available?}
    E -->|Yes| F1[Phase 2A: System Identification\nOnline Mode]
    E -->|No|  F2[Phase 2B: System Identification\nOffline Mode]
    F1 --> G[Phase 3: Method & Format Discovery]
    F2 --> G
    G --> H[Phase 4: Prompt Construction\nSynthesis & Verification]
    H --> I[Phase 5: Delivery\nOptimized Prompt • Confidence • Fallbacks]
    I --> J([Governance Architecture\nMeta-Learning • Loop Prevention • Confidence])

    %% Styling (kept subtle for dark/light modes)
    classDef phase fill:#f8f9fa,stroke:#8a8a8a,color:#111;
    classDef decision fill:#fff3cd,stroke:#8a8a8a,color:#111;
    classDef gov fill:#e9ecef,stroke:#6c6c6c,color:#111,font-weight:bold;

    class B,C,D,F1,F2,G,H,I phase;
    class E decision;
    class J gov;
