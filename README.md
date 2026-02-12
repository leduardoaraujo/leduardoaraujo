# Luiz Araujo 
- Python Developer — Data Systems

```mermaid
flowchart LR
    A[APIs / Files / Queues] --> B[Ingestion Layer]
    B --> C[Validation & Contracts]
    C --> D[Transformation Engine]
    D --> E[(Postgres / DuckDB)]
    E --> F[APIs / BI / Analytics]

    D --> G[Structured Logs]
    C --> H[Quality Checks]
