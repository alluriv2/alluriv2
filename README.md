<p align="center">
  <img src="assets/banner.svg" alt="Vaibhav Alluri, Data Engineer. Building reliable data platforms across every layer." width="100%">
</p>

<p align="center">
  <a href="https://linkedin.com/in/vaibhavalluri"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  <a href="mailto:vaibhav.sai5076@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"></a>
  <a href="https://alluriv.dev"><img alt="Portfolio" src="https://img.shields.io/badge/Portfolio-111827?style=for-the-badge&logo=vercel&logoColor=white"></a>
</p>

## Hi, I’m Vaibhav 👋

I’m a data engineer who enjoys connecting infrastructure, pipelines, storage, APIs, and observability into one dependable platform.

I’m especially interested in what happens beyond the happy path: delayed events, duplicate messages, stale data, interrupted services, and systems that need to remain reliable as they scale.

- 🔭 Building and validating cloud infrastructure for a public-health data platform
- ⚙️ Working across batch processing, event streaming, and platform operations
- 🌱 Exploring Java, Spring Boot, and Databricks more deeply
- 📍 Based in New Jersey
- 📝 Sharing architecture, case studies, and engineering notes at [alluriv.dev](https://alluriv.dev)

---

## ⚙️ What I Build

<table>
  <tr>
    <td width="33%" valign="top">
      <h3>🌊 Data Pipelines</h3>
      Batch and streaming workflows that move data reliably from ingestion to delivery.
    </td>
    <td width="33%" valign="top">
      <h3>☁️ Cloud Platforms</h3>
      Infrastructure that brings compute, storage, networking, and observability together.
    </td>
    <td width="33%" valign="top">
      <h3>🧠 Applied Intelligence</h3>
      Analytics, machine learning, and AI used where they add practical value.
    </td>
  </tr>
</table>

---

## 🚀 Selected Work

### Weather Analytics Platform

A recoverable, event-driven platform for historical and live weather observations. The system combines Kafka, PostgreSQL, Spring Boot, and Kubernetes with replay-safe processing, automated reconciliation, and end-to-end observability.

### Counterfactual Analysis of EMS Stroke Response

A healthcare data pipeline and modeling framework designed to study the factors associated with prolonged EMS scene time and evaluate how selected interventions might change model predictions.

### Azure Public-Health Data Platform

Private Azure infrastructure integrating Kubernetes, streaming, relational and object storage, secure networking, container delivery, and observability for a public-health modernization initiative.

### Enterprise Analytical Data Warehouse

A dimensional warehouse with historical tracking, incremental loading, staged transformations, analytical aggregates, and automated reconciliation.

> Explore the architecture, decisions, and tradeoffs behind the work at [alluriv.dev](https://alluriv.dev).

---

## 🧩 When Systems Push Back

### Duplicate events after consumer lag

A consumer fell behind, and a live producer began republishing history it had already sent. I traced the duplication through producer logs and processing watermarks to a stale fallback timestamp, corrected the source behavior, and verified the fix through a complete ingestion run.

### Healthy container. Silent consumer.

A Kafka consumer had left its group while its container continued passing infrastructure health checks. The dashboard stayed online but served stale data. I added a consumer watchdog and a data-freshness endpoint so health reflected whether the pipeline was actually progressing.

### The request worked everywhere except the browser

The API succeeded through command-line clients but failed in real browsers. Browser testing exposed a CORS configuration gap, and an explicit origin allowlist resolved it.

---

## 🧰 Engineering Toolkit

<p align="center">
  <img alt="Python, Java, PostgreSQL, MySQL, Kafka, FastAPI, Docker, Kubernetes, Terraform, Azure, AWS, GitHub Actions, Grafana, and Prometheus" src="https://skillicons.dev/icons?i=python,java,postgres,mysql,kafka,fastapi,docker,kubernetes,terraform,azure,aws,githubactions,grafana,prometheus&perline=7">
</p>

<p align="center">
  <strong>Languages</strong> · Python, Java, SQL<br>
  <strong>Data</strong> · Kafka, PostgreSQL, DuckDB, PyArrow<br>
  <strong>Cloud and platform</strong> · Azure, AWS, Docker, Kubernetes, Terraform<br>
  <strong>Delivery and observability</strong> · GitHub Actions, Prometheus, Grafana
</p>

---

## 🧭 The Path So Far

- **Global Infrastructure Services** — Cloud and data-platform infrastructure supporting public-health modernization
- **Clarkson University** — Graduate work spanning data engineering and healthcare data science
- **Amazon** — Risk and compliance work involving complaint, appeal, and classifier-performance analysis
- **M.S. in Applied Data Science** — Clarkson University, 4.0 GPA

---

## 🤝 Let’s Connect

I’m always interested in thoughtful conversations about data engineering, distributed systems, cloud platforms, and the lessons hidden inside difficult failures.

<p align="center">
  <a href="https://linkedin.com/in/vaibhavalluri">LinkedIn</a>
  ·
  <a href="mailto:vaibhav.sai5076@gmail.com">Email</a>
  ·
  <a href="https://alluriv.dev">Portfolio</a>
</p>
