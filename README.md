
  ## Luiz E. Araujo  
  ```
    Contact: luiz.dataeng@gmail.com
    Open to data engineering projects
```
### > whoami
```bash
Developer specializing in scalable data pipelines
Creator of ForgeFlow - modern async ETL framework
Focus: API ingestion, transformation, multi-warehouse distribution
```
### > tech-stack --list
```yaml
databases:
  - PostgreSQL
  - DuckDB
  - BigQuery
  - Snowflake
  - MongoDB

orchestration:
  - Apache Airflow
  - FastAPI
  - Async/Await

python_tools:
  - Pydantic (validation)
  - Pandas (transformation)
  - HTTPX (async requests)
  - Structlog (observability)
```
### > pipeline-diagram --render
```mermaid
flowchart LR
    A[APIs / Files / Queues] --> B[Ingestion Layer]
    B --> C[Validation & Contracts]
    C --> D[Transformation Engine]
    D --> E[(Postgres / DuckDB)]
    E --> F[APIs / BI / Analytics]
    D --> G[Structured Logs]
    C --> H[Quality Checks]
```
