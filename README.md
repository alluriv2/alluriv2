## Vaibhav Alluri — Data Engineer

I build reliable data pipelines teams can trust: event-driven ingestion with Kafka, idempotent storage in PostgreSQL, and automated delivery to the cloud.

- **Now:** Data Engineer at Global Infrastructure Services. I provisioned a private-networked Azure environment (AKS, HDInsight Kafka, SQL Server, Key Vault) for a public-health data platform, adapted its Terraform modules and Helm charts, and wrote the deployment runbooks and readiness criteria for its move from proof of concept to pilot.
- **Before:** Amazon, as a Data Analyst (Risk Operations) and Business Analyst (Product Compliance). Root-cause analysis of customer complaints contributed to a 45% reduction in complaint rates. Analysis of seller appeals helped lift a compliance classifier's accuracy from 46% to 65%.
- **Education:** MS in Applied Data Science, Clarkson University (4.0 GPA).

[Portfolio](https://alluriv.dev) · [LinkedIn](https://linkedin.com/in/vaibhavalluri) · vaibhav.sai5076@gmail.com

---

### Featured projects

**[Real-Time Telemetry Analytics Platform](https://github.com/alluriv2/real-time-telemetry-analytics-platform)** · Python, Kafka, PostgreSQL, FastAPI, Plotly Dash, Docker Compose, AWS Lightsail, GitHub Actions
An end-to-end platform for weather-station telemetry. Historical and live data take the same path through Kafka, and a batch consumer writes 1,000 records per PostgreSQL transaction, committing Kafka offsets only after the database commit, so replays never create duplicates. GitHub Actions runs tests and builds on every push and deploys to AWS Lightsail once CI passes on `main`.

**[Enterprise Analytical Data Warehouse](https://github.com/alluriv2/enterprise-analytical-data-warehouse)** · SQL, MySQL, stored procedures
Sales and rental sources conformed into one star schema, with stored-procedure ETL, daily and late-arriving fact refreshes, aggregate and snapshot tables, and Slowly Changing Dimension (Type 2) history on Product and Customer.

**[Real-Time Weather Analytics on Kubernetes](https://github.com/alluriv2/Weather-Analytics-Platform)** · Python, Kafka, PostgreSQL, Kubernetes, Prometheus, Grafana
The same event-driven design run on a local Kubernetes cluster: ordered startup and shutdown, durable per-station ingestion watermarks, scheduled reconciliation, and a provisioned Grafana dashboard.

**[911CallSight](https://github.com/alluriv2/911CallSight)** · Python, Whisper, Mistral (Ollama), PostgreSQL, Flask
Transcribes emergency-call audio, extracts structured incident data with a locally run LLM, stores it in PostgreSQL, and serves it through an API.

**[Weather Data Ingestion Pipeline](https://github.com/alluriv2/weather-data-ingestion-pipeline)** · Python, DuckDB, Flask, Plotly
Incremental, idempotent ingestion of live weather-station logs, with a dashboard for inspecting the data.

**[YourFlix](https://github.com/alluriv2/YourFlix)** · Swift, SwiftUI
A native macOS app that turns folders of personal photos and videos into a streaming-style library.

Also: a Java and Spring Boot version of the weather platform on Kubernetes (600K+ real observations per station ingested, zero data loss across repeated restarts), and a counterfactual analysis of EMS stroke response times on the 2024 NEMSIS national dataset (XGBoost baseline ROC-AUC 0.828).

---

### Tools
**Data and streaming:** Python · SQL · Java · Apache Kafka · PostgreSQL · DuckDB · Parquet
**Cloud and delivery:** Azure · AWS · Docker · Kubernetes · Terraform · Helm · GitHub Actions
**APIs and monitoring:** FastAPI · Spring Boot · Prometheus · Grafana
