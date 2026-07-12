# Portfolio Content Update — Matches Resume Exactly

Paste these sections into your site (akhila8978.github.io) to replace the current copy.
Every stat, tool, and claim below is pulled directly from your resume — nothing here should
say anything your resume doesn't also say.

---

## Hero Section

**Tagline (replace "// Data Engineer · AWS · Snowflake · PySpark · dbt"):**
```
// Data Engineer · AWS · Snowflake · PySpark · Databricks
```
*(Remove "dbt" from the hero tagline — it's a "Currently Building" skill, not a working tool. Keep it out of anything that reads as a claimed proficiency.)*

**Intro paragraph (replace the "Engineering scalable, high-availability..." paragraph):**
```
Data Engineer (currently titled System Engineer) with 2.5 years of consulting and
enterprise IT experience building ETL/ELT pipelines, CDC-based ingestion, and cloud
data platforms across AWS, Snowflake, and Databricks — supporting client-facing
production workloads processing 1M+ records/day at TCS.
```

**Stat tiles (replace 40% / 1M+ / 99.9% / 5):**
```
25%      Query performance improvement
1M+      Records/day processed
99%+     SLA compliance
2.5      Years of DE experience
```
*(These are the real, resume-backed numbers. "40% faster pipelines" and "99.9% SLA uptime" don't exist anywhere on your resume — drop them.)*

**Buttons:** Keep GitHub + LinkedIn links, both already correct.

---

## Skills Section

Replace the entire skills grid with exactly what's on the resume — **remove Terraform, EMR, Kinesis, Step Functions, MWAA, Great Expectations, GitHub Actions, MS Purview, Splunk**. None of these are on your resume, and a hiring manager who sees them here and not there will assume one document is wrong.

```
Languages
Python · Advanced SQL · PySpark · Shell/Bash

AWS Cloud
S3 · Glue · Lambda · CloudWatch · Redshift · IAM · EventBridge

Data Platforms
Snowflake (Streams, Tasks, Snowpipe, RBAC, clustering, materialized views) · Amazon Redshift

Databricks & Lakehouse
Apache Spark · Delta Lake · Delta Live Tables · Lakehouse architecture · Unity Catalog ·
Lakeflow Connect · Databricks Git Folders · Declarative Automation Bundles · CI/CD

AI / GenAI
RAG pipelines · embeddings · vector search · LLM integration (OpenAI API) ·
prompt-to-response orchestration · FastAPI-served AI applications

DevOps & Backend
Git · GitHub · CI/CD · Docker · FastAPI · Linux/Unix · JIRA · Agile/Scrum

Currently Building
dbt · Apache Airflow · Kafka — applied hands-on in personal projects
```

---

## Experience Section

**Title (replace "Systems Engineer — Data Engineering & Production Support"):**
```
System Engineer — Data Engineering & Cloud Support
Mar 2024 – Present · Tata Consultancy Services (TCS) · Hyderabad, India
```

**Tags (replace the pill list — remove Terraform, Splunk):**
```
Python · PySpark · SQL · AWS Glue · Snowflake · AWS S3 · AWS Lambda · Amazon Redshift · CloudWatch · Git · Agile
```

**Bullets — replace all 8 bullets with these (identical to resume, zero embellishment):**
```
- Built Python- and PySpark-based ETL/ELT pipelines moving structured data across
  source systems, AWS S3, and Amazon Redshift, supporting 10+ daily production
  workflows processing 1M+ records/day with zero data loss.

- Implemented Snowflake Streams and Tasks for CDC pipelines, automating incremental
  ingestion and enabling near-real-time data availability for downstream consumers;
  supported migration of legacy workloads to Snowflake for improved scalability.

- Designed multi-stage data validation and data quality frameworks — schema checks,
  null handling, accuracy verification — maintaining 99%+ SLA compliance.

- Monitored production pipelines via AWS CloudWatch, performed root cause analysis
  on failures, and maintained incident runbooks — reducing recurring incidents by
  20% and cutting resolution time by 35%.

- Optimized complex SQL (CTEs, window functions, MERGE, multi-table joins) across
  Snowflake and Redshift, improving query performance by 25%.

- Reduced ETL pipeline failure rate by 30% through proactive AWS Glue monitoring
  and structured debugging; operated event-driven AWS Lambda functions with
  CloudWatch-based failure diagnosis.

- Collaborated cross-functionally with BI, analytics, and application engineering
  teams — including client stakeholders — to translate business requirements into
  technical pipeline specifications within Agile/Scrum sprints using JIRA.
```

**Stat tiles under Experience (replace 40% / 35% / 30% / 30min):**
```
25%      Query performance
30%      Fewer pipeline failures
35%      Faster incident resolution
20%      Fewer recurring incidents
```

---

## Projects Section

Replace all three current project cards with these three — matching the resume's project set exactly. This also drops the "Serverless Real-Time ETL" and "PySpark Batch Processing Pipeline" cards, which describe tools (EMR, Kinesis, Step Functions, Terraform) that aren't on your resume and that you should be ready to defend line-by-line in an interview if they stay public anywhere.

**Card 1:**
```
🏆 1st Place — TCS AI Fridays S2 (internal hackathon)

Contract Intelligence Platform

Multi-stage RAG pipeline for contract clause extraction and legal risk review —
document ingestion → embedding → semantic vector retrieval → LLM inference →
structured JSON response, served via a FastAPI REST backend with async processing.
Reduced manual review time from hours to sub-minute AI-assisted analysis.

Python · FastAPI · OpenAI API · RAG Pipeline · LLM Integration · AWS · REST API · Vector Search

↗ github.com/akhila8978
```
*(Note: I relabeled this "internal hackathon" instead of "production" — see below on why.)*

**Card 2:**
```
Personal Project

Retail Order Pipeline — Raw → Curated → Analytics

Multi-layer Snowflake data pipeline (raw → curated → analytics) ingesting retail
order data. Built ELT logic for schema validation and deduplication in the curated
layer, producing analytics-ready tables using CTEs and window functions. Snowflake
Streams and Tasks automate incremental loads between layers.

Snowflake · SQL · Python · ETL/ELT · Data Modeling · Streams & Tasks

↗ github.com/akhila8978
```

**Card 3:**
```
Personal Project

Python ETL Utility Library

Modular Python ETL utility library with pluggable ingestion readers, S3/Boto3
integration, structured logging, and reusable error-handling decorators — reducing
boilerplate by ~40% and standardizing error handling.

Python · OOP · Decorators · AWS S3 · Boto3 · Git · CI/CD

↗ github.com/akhila8978
```

---

## Certifications Section

Remove **AWS Certified DevOps Engineer – Professional** entirely. Replace the full list with:

```
Databricks Certified Data Engineer Associate — Valid through Jun 2028
AWS Certified Developer – Associate — Valid Jan 2029
AWS Certified AI Practitioner — Valid Jul 2028
Google Cloud Generative AI Leader — Valid Oct 2028
Microsoft Power BI Data Analyst Associate (PL-300) — Valid 2027
SnowPro Core Certification (COF-C03) — In Progress, 2026
```

---

## Contact Section

Fix the portfolio link in the footer — it currently points to `akhila-portfolio.github.io`, which is a different (likely dead) URL than your actual live site `akhila8978.github.io`. Update it to:
```
🌐 https://akhila8978.github.io
```

---

## One judgment call worth your input: "production-grade" language

Your resume and the portfolio both currently call the Contract Intelligence Platform
"production-grade." If this only ran as a hackathon/demo (not something actual users
or clients used ongoing), I'd soften this on both documents — a technical interviewer
will ask "who used this in production and at what volume," and "it was a hackathon
entry" as the real answer after "production-grade" framing costs you more trust than
describing it accurately from the start. If it genuinely was deployed for real use
after the hackathon, ignore this note and keep the current framing — just make sure
you can describe the actual usage/traffic if asked.
