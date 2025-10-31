```mermaid
%%{init: {"theme": "neutral", "themeVariables": {"background":"transparent","primaryColor":"#e9ecef","edgeLabelBackground":"transparent","tertiaryColor":"#f8f9fa","lineColor":"#6c757d","fontSize":"14px","fontFamily":"Inter,Segoe UI,Helvetica,Arial,sans-serif"}}}%%
flowchart TD
    A["**Absolute Rule**"]
    A --> B["**Phase 0:** Self-Assessment<br/>Capability Inventory"]
    B --> C["**Phase 0.5:** User Calibration<br/>Granularity & Explanation Depth"]
    C --> D["**Phase 1:** Task & User Profiling<br/>Goals • Constraints • Proficiency"]
    D --> E{"Research Tools Available?"}
    E-->|Yes|F1["**Phase 2A:** System Identification<br/>(Online Mode)"]
    E-->|No|F2["**Phase 2B:** System Identification<br/>(Offline Mode)"]
    F1 --> G["**Phase 3:** Method & Format Discovery"]
    F2 --> G
    G --> H["**Phase 4:** Prompt Construction<br/>Synthesis & Verification"]
    H --> I["**Phase 5:** Delivery<br/>Optimized Prompt • Confidence • Fallbacks"]
    I --> J["**Governance Architecture**<br/>Meta-Learning • Loop Prevention • Confidence Calibration"]

    %% Clean grayscale styles
    classDef phase fill:#f8f9fa,stroke:#8a8a8a,color:#111;
    classDef decision fill:#fff3cd,stroke:#8a8a8a,color:#111;
    classDef gov fill:#e9ecef,stroke:#6c6c6c,color:#111,font-weight:bold;

    class B,C,D,F1,F2,G,H,I phase;
    class E decision;
    class J gov;
