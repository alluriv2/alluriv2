<p align="center">
  <img src="assets/banner.svg" alt="Vaibhav Alluri, Data Engineer. Event-driven pipelines with Kafka, PostgreSQL, Azure and AWS." width="100%">
</p>

<p align="center">
  <a href="https://linkedin.com/in/vaibhavalluri"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge"></a>
  <a href="mailto:vaibhav.sai5076@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"></a>
  <a href="https://alluriv.dev"><img alt="Portfolio" src="https://img.shields.io/badge/Portfolio-111827?style=for-the-badge"></a>
</p>

<p align="center">
  I build data pipelines that keep working when things fail: replay-safe, recoverable, and deployed end to end.
</p>

### By the numbers

<table align="center">
  <tr>
    <td align="center" width="25%"><h2>600K+</h2>real observations ingested per station<br/><sub>Java weather platform</sub></td>
    <td align="center" width="25%"><h2>1.9M</h2>messages streamed in one verification run<br/><sub>Java weather platform</sub></td>
    <td align="center" width="25%"><h2>0</h2>records lost across repeated stop and restart cycles<br/><sub>Java weather platform</sub></td>
    <td align="center" width="25%"><h2>45%</h2>drop in customer complaint rates<br/><sub>Amazon, Risk Operations</sub></td>
  </tr>
</table>

### Problems I've solved

- **1.25 million duplicate messages.** After a consumer fell behind, a live producer republished history it had already sent. I traced it through the producer logs and the watermark table to a stale fallback timestamp, fixed it at the source, and verified the fix in production.
- **A consumer that went silent while every health check stayed green.** It had left its Kafka group but its container stayed up, so the dashboard served stale data. I added a watchdog that restarts it and a data-freshness health endpoint that an uptime monitor can watch.
- **A CORS failure only a browser could see.** Requests worked in curl and failed in real browsers. Testing in a browser found it, and an origin allowlist fixed it.

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
