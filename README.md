<p align="center">
  <img src="assets/banner.svg" alt="Vaibhav Alluri, Data Engineer. Data systems that stay resilient when the real world gets messy." width="100%">
</p>

<p align="center">
  <a href="https://linkedin.com/in/vaibhavalluri"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge"></a>
  <a href="mailto:vaibhav.sai5076@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"></a>
  <a href="https://alluriv.dev"><img alt="Portfolio" src="https://img.shields.io/badge/Portfolio-111827?style=for-the-badge"></a>
</p>

I'm a data engineer who connects infrastructure, pipelines, storage, APIs and observability into one dependable platform.

I'm most interested in what happens beyond the happy path: delayed events, duplicate messages, stale data, interrupted services, and systems that have to stay reliable as they grow. I write about the architecture decisions and tradeoffs behind my work at [alluriv.dev](https://alluriv.dev).

### What failures have taught me

- **Assume messages arrive twice, late, or out of order.** Design every write so a replay changes nothing.
- **A green health check should mean data is flowing.** A running container is not the same as a working pipeline.
- **Test where the user is.** If it only works from the command line, it does not work yet.

### When systems push back

**Duplicate events after consumer lag.** A consumer fell behind, and a live producer began republishing history it had already sent. I traced it through producer logs and processing watermarks to a stale fallback timestamp, corrected the source behavior, and verified the fix in production.

**Healthy container, silent consumer.** A Kafka consumer had left its group while its container kept passing infrastructure health checks, so the dashboard stayed online and served stale data. I added a watchdog and a data-freshness endpoint so health reflects whether the pipeline is actually progressing.

**The request worked everywhere except the browser.** The API succeeded from command-line clients and failed in real browsers. Browser testing exposed a CORS gap, and an explicit origin allowlist resolved it.

### Path

- **Global Infrastructure Services:** Data Engineer, building cloud and data-platform infrastructure for a public-health data platform
- **Amazon:** risk and compliance analytics
- **Clarkson University:** M.S. in Applied Data Science
- **Databricks Certified Data Engineer Associate**

### Tools

<p align="center">
  <img alt="Python, Java, PostgreSQL, MySQL, Kafka, DuckDB, FastAPI, Docker, Kubernetes, Terraform, Azure, AWS, GitHub Actions, Grafana, Prometheus" src="https://skillicons.dev/icons?i=python,java,postgres,mysql,kafka,duckdb,fastapi,docker,kubernetes,terraform,azure,aws,githubactions,grafana,prometheus&perline=15">
</p>
