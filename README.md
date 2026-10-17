<h1 align="center">Vaibhav Alluri</h1>

<p align="center">
  <b>Data Engineer</b> · Kafka · Python · PostgreSQL · Azure &amp; AWS · Ex-Amazon
</p>

<p align="center">
  <a href="https://linkedin.com/in/vaibhavalluri"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge"></a>
  <a href="mailto:vaibhav.sai5076@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"></a>
  <a href="https://alluriv.dev"><img alt="Portfolio" src="https://img.shields.io/badge/Portfolio-111827?style=for-the-badge"></a>
</p>

<p align="center">
  I build data pipelines that keep working when things fail: replay-safe, recoverable, and deployed end to end.
</p>

```mermaid
flowchart LR
    A[Live and historical<br/>sensor data] --> B[Kafka]
    B --> C[Consumer<br/>idempotent writes]
    C --> D[(PostgreSQL)]
    D --> E[Aggregates]
    D --> F[REST API]
    E --> G[Live dashboard]
    F --> G
    H[GitHub Actions<br/>CI/CD] -.->|deploys| B
    H -.->|deploys| G
```

### Featured projects

| Project | What it shows |
|---|---|
| **[Real-Time Telemetry Analytics Platform](https://github.com/alluriv2/real-time-telemetry-analytics-platform)**<br/>Kafka · PostgreSQL · FastAPI · Dash · AWS | End-to-end: ingestion, storage, API, live dashboard. 1,000-record batches, Kafka offsets committed after the database commit, auto-deploy once CI passes |
| **[Enterprise Analytical Data Warehouse](https://github.com/alluriv2/enterprise-analytical-data-warehouse)**<br/>SQL · MySQL | Sales and rental sources in one star schema, late-arriving fact handling, SCD Type 2 history |
| **[Weather Analytics on Kubernetes](https://github.com/alluriv2/Weather-Analytics-Platform)**<br/>Kafka · Kubernetes · Prometheus · Grafana | Same design on Kubernetes: ordered startup, per-station watermarks, scheduled reconciliation |
| **[911CallSight](https://github.com/alluriv2/911CallSight)**<br/>Whisper · Ollama · PostgreSQL · Flask | Audio to structured, queryable incident data with a local LLM |
| **[Weather Data Ingestion Pipeline](https://github.com/alluriv2/weather-data-ingestion-pipeline)**<br/>Python · DuckDB | Incremental, idempotent ingestion of live station logs |
| **[YourFlix](https://github.com/alluriv2/YourFlix)**<br/>Swift · SwiftUI | Native macOS app that turns photo folders into a streaming-style library |

Also built: a Java and Spring Boot version of the weather platform (600K+ observations per station, zero data loss across restarts) and a counterfactual analysis of EMS stroke response times on the 2024 NEMSIS dataset.

### Experience

| | |
|---|---|
| **Now** | Data Engineer, Global Infrastructure Services: private-networked Azure environment (AKS, HDInsight Kafka, SQL Server) for a public-health data platform, with runbooks and readiness criteria for its move to pilot |
| **Before** | Amazon, Data Analyst and Business Analyst: complaint analysis behind a 45% drop in complaint rates; appeal analysis that lifted a compliance classifier from 46% to 65% accuracy |
| **Education** | MS Applied Data Science, Clarkson University (4.0 GPA) |

### Tools

<p align="center">
  <img alt="Python, Java, PostgreSQL, MySQL, Kafka, DuckDB, FastAPI, Docker, Kubernetes, Terraform, Azure, AWS, GitHub Actions, Grafana, Prometheus" src="https://skillicons.dev/icons?i=python,java,postgres,mysql,kafka,duckdb,fastapi,docker,kubernetes,terraform,azure,aws,githubactions,grafana,prometheus&perline=15">
</p>
