# Contexta-ML
This repo explains the ML Architecture and contains the code, dataset required for the project. 

flowchart TD

%% Data Sources
A[NVD CVE Feed]
B[Synthetic SIEM Logs]
C[External Data]

%% Data ingestion
D[Data Ingestion]

%% ML Part
E[ML Part<br/>Hema]

%% Backend modules
F[Vulnerabilities Top 10]
G[Digital Twin]
H[Multi Agent SOC (xAI)]
I[Executive View]
J[Blockchain Based Ledger]

%% Frontend
K[SIEM Dashboard<br/>Frontend - Next.js]

%% Flow
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

%% Colors (Pastel Theme)
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

style K fill:#B2EBF2,stroke:#333flowchart TD

%% Data Sources
A[NVD CVE Feed]
B[Synthetic SIEM Logs]
C[External Data]

%% Data ingestion
D[Data Ingestion]

%% ML Part
E[ML Part<br/>Hema]

%% Backend modules
F[Vulnerabilities Top 10]
G[Digital Twin]
H[Multi Agent SOC (xAI)]
I[Executive View]
J[Blockchain Based Ledger]

%% Frontend
K[SIEM Dashboard<br/>Frontend - Next.js]

%% Flow
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

%% Colors (Pastel Theme)
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
