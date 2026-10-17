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
