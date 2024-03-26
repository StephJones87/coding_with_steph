# coding_with_steph
```mermaid
graph TB
    A[Healthcare and Pharmacy] -->|Part of| B[Pharmacist]
    A --> C[Royal Pharmaceutical Society]
    A --> D[BNF]
    A --> E[Stockley's Drug Interactions]
    A --> F[Hospital Pre-registration]
    A --> G[CPD]
    A --> H[Clinical Professional]

    B --> I[Regulation and Safety]
    C --> I
    D --> J[Data and Interoperability]
    E --> J
    F --> K[Genomics and Education]
    G -.-> L[Data Science and Engineering]
    H -.-> M[Software Development]

    I -->|Overseen by| N[MHRA]
    I -->|Focus on| O[Pharmacovigilance]
    I -->|Concerned with| P[ADR]
    I --> J

    J -->|Enables| Q[Interoperability]
    J -->|Includes| R[SNOMED]
    J -->|Includes| S[OMOP]
    J -->|Includes| T[ICD10]
    J -->|Includes| U[FHIR]
    J -->|Utilizes| V[Big Data]
    J -->|Defines| W[Terminologies]

    K -->|Program at| X[Imperial College London]
    K -->|Focuses on| Y[Pharmacogenomics]
    K -->|Related to| Z[Genetic Data]
    K -->|Degree| AA[MSc Genomic Medicine]
    Y --> J
    Z -.-> J

    L -->|Role| AB[Data Engineer]
    L -->|Field| AC[Data Science]
    L -->|Uses| AD[Python]
    L -->|Uses| AE[SQL]
    L --> J

    M -->|Involves| AF[Version Control]
    M -->|Utilizes| AG[Cloud Computing]
    M -->|Platforms| AH[AWS]
    M -->|Platforms| AI[Azure]
    M -->|Platforms| AJ[Databricks]
    AG --> J
