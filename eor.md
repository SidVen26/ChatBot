```mermaid
graph LR;
    A["Starting type: 30 amps"] --> B[15 amps]
    B --> C[15 Amps]
    C --> D[15 amps]
    D --> E["15 amps (update Erd_powercordType)"]

    %% Styling
    style A fill:#4CAF50,stroke:#333,stroke-width:2px,color:#fff
    style B fill:#2196F3,stroke:#333,stroke-width:2px,color:#fff
    style C fill:#2196F3,stroke:#333,stroke-width:2px,color:#fff
    style D fill:#2196F3,stroke:#333,stroke-width:2px,color:#fff
    style E fill:#FF9800,stroke:#333,stroke-width:2px,color:#fff
