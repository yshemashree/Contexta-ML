## System Architecture

```mermaid
flowchart TB

%% DATA SOURCES
subgraph Data Sources
A[NVD CVE Feed]
B[Synthetic SIEM Logs]
C[External Data]
end

%% INGESTION
D[Data Ingestion]

%% BACKEND
subgraph Backend (FastAPI)

E[ML Part<br/>Hema]

F[Vulnerabilities Top 10]
G[Digital Twin]

H[Multi-Agent SOC (xAI)]
I[Executive View]

J[Blockchain Based Ledger]

end

%% FRONTEND
K[SIEM Dashboard<br/>Frontend - Next.js]

%% FLOWS
A --> D
B --> D
C --> D

D --> E

E --> F
F --> G
G --> J

D --> H
H --> I
I --> J

J --> K

%% PASTEL COLORS
style A fill:#E3F2FD,stroke:#333
style B fill:#EDE7F6,stroke:#333
style C fill:#F3E5F5,stroke:#333

style D fill:#FFF9C4,stroke:#333

style E fill:#C8E6C9,stroke:#333
style F fill:#C8E6C9,stroke:#333
style G fill:#C8E6C9,stroke:#333

style H fill:#E1BEE7,stroke:#333
style I fill:#F8BBD0,stroke:#333

style J fill:#FFE0B2,stroke:#333

style K fill:#B2EBF2,stroke:#333
```
