## System Architecture

```mermaid
flowchart TD

A[NVD CVE Feed] --> D[Data Ingestion]
B[Synthetic SIEM Logs] --> D
C[External Data] --> D

D --> E[ML Part<br/>Hema]

E --> F[Vulnerabilities Top 10]
F --> G[Digital Twin]
G --> J[Blockchain Based Ledger]

D --> H[Multi Agent SOC (xAI)]
H --> I[Executive View]
I --> J

J --> K[SIEM Dashboard<br/>Frontend - Next.js]

style A fill:#E3F2FD,stroke:#333
style B fill:#EDE7F6,stroke:#333
style C fill:#F3E5F5,stroke:#333
style D fill:#FFF9C4,stroke:#333
style E fill:#E8F5E9,stroke:#333
style F fill:#E8F5E9,stroke:#333
style G fill:#E8F5E9,stroke:#333
style H fill:#E1BEE7,stroke:#333
style I fill:#F8BBD0,stroke:#333
style J fill:#FFE0B2,stroke:#333
style K fill:#B2EBF2,stroke:#333
