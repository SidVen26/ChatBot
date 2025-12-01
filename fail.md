```mermaid

graph LR;
    A["Starting type: 30 amps"] --> B["15 amps"]
    B --> C["15 amps"]
    C --> D["20 amps"]
    D --> E["20 amps"]
    E --> F["Final Type: 30 amps (Erd_powercordType does NOT update)"]

    %% Styling
    style A fill:#4CAF50,stroke:#333,stroke-width:2px,color:#fff   %% Green for start
    style B fill:#2196F3,stroke:#333,stroke-width:2px,color:#fff   %% Blue for 15 amps
    style C fill:#2196F3,stroke:#333,stroke-width:2px,color:#fff   %% Blue for 15 amps
    style D fill:#FF9800,stroke:#333,stroke-width:2px,color:#fff   %% Orange for 20 amps
    style E fill:#FF9800,stroke:#333,stroke-width:2px,color:#fff   %% Orange for 20 amps
    style F fill:#F44336,stroke:#333,stroke-width:2px,color:#fff   %% Red for last node
