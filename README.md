<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=220&section=header&text=Shubhangi%20Goyal&fontSize=42&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Data%20Engineering%20%7C%20AWS%20%26%20Databricks%20Pipelines&descAlignY=55&descSize=18" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=A78BFA&center=true&vCenter=true&width=650&lines=Data+Engineering+Student+%40+VIT+Vellore;Building+Pipelines+on+AWS+%26+Databricks;SQL+%7C+PySpark+%7C+Dimensional+Modeling+%7C+SCD+Type+2;AWS+Solutions+Architect+Associate+(In+Progress)" alt="Typing SVG" />

<br/>

![VIT Vellore](https://img.shields.io/badge/VIT_Vellore-CGPA_8.45-6D28D9?style=for-the-badge&logo=googlescholar&logoColor=white)
![Location](https://img.shields.io/badge/India-Tamil_Nadu-4C1D95?style=for-the-badge&logo=googlemaps&logoColor=white)

<br/>

[![Portfolio](https://img.shields.io/badge/Portfolio-8B5CF6?style=for-the-badge&logo=vercel&logoColor=white)](https://github.com/goyalshubhi)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-7C3AED?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/shubhangi-goyal-4a148b26a)
[![Email](https://img.shields.io/badge/Email-6D28D9?style=for-the-badge&logo=gmail&logoColor=white)](mailto:shubhangigoyal27@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-5B21B6?style=for-the-badge&logo=github&logoColor=white)](https://github.com/goyalshubhi)

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=goyalshubhi&color=8b5cf6&style=for-the-badge&label=PROFILE+VIEWS)
![Followers](https://img.shields.io/github/followers/goyalshubhi?style=for-the-badge&color=7c3aed&labelColor=1e1e2e)
![Stars](https://img.shields.io/github/stars/goyalshubhi?style=for-the-badge&color=6d28d9&labelColor=1e1e2e)

</div>

<br/>

## 🪷 About Me

```yaml
name: "Shubhangi Goyal"
role: "Data Engineering Student"
university: "VIT Vellore — B.Tech CSE, 2023-2027 (Expected)"
cgpa: "8.45 / 10"
focus:
  - "Cloud data pipelines on AWS & Databricks"
  - "Dimensional modeling, SCD Type 2, entity resolution"
  - "SQL & data warehousing (Glue Catalog, Athena)"
  - "AWS-native RAG pipeline design (Bedrock, OpenSearch, DynamoDB)"
open_to:
  - "Data Engineering fresher roles"
  - "Cloud/Backend data pipeline internships"
```

I'm a pre-final year CSE student at VIT Vellore who builds real, end-to-end data pipelines rather than tutorial projects — dimensional warehouses on AWS Glue/Athena, SCD Type 2 history tracking on Databricks with Spark Declarative Pipelines, and an AWS-native RAG pipeline for support-ticket resolution. I care about pipelines that are technically defensible: every project below documents the real bugs I found and fixed while building it.

<br/>

## 🛠️ Tech Stack

<div align="center">

**Languages**

![Python](https://skillicons.dev/icons?i=python) ![Cpp](https://skillicons.dev/icons?i=cpp) 

**Cloud, Big Data & Tooling**

![AWS](https://skillicons.dev/icons?i=aws) ![Git](https://skillicons.dev/icons?i=git) ![GithubActions](https://skillicons.dev/icons?i=githubactions)

</div>

| Category | Skills |
|---|---|
| **Languages** | Python, SQL, C++ |
| **Big Data & Cloud** | PySpark, Apache Spark, Spark Declarative Pipelines, Apache Airflow, Databricks, AWS (S3, Lambda, SQS, SNS, CloudWatch, Bedrock, OpenSearch, DynamoDB, IAM) |
| **Data Modeling & Warehousing** | Dimensional Modeling (Star Schema), SCD Type 2, Entity Resolution, Data Warehousing, Data Quality Validation, AWS Glue Catalog, Amazon Athena |
| **GenAI / LLM** | RAG Pipeline Design, LLM APIs (Groq, Gemini, Bedrock Titan), AI-Assisted Development (Claude, GitHub Copilot) |
| **Tools** | Git, GitHub Actions, Streamlit, boto3, REST APIs |

<br/>

## 🚀 Featured Projects

<details>
<summary><b>⚡ PayWatch — AWS Pipeline Observability Framework</b></summary>
<br/>

Automated pipeline-failure diagnosis across Apache Airflow DAGs, replacing manual on-call investigation with evidence-based anomaly fingerprinting.

| | |
|---|---|
| **Stack** | Airflow, AWS (S3, Glue, Athena, SNS, CloudWatch), Python, networkx |
| **Scale** | 50 Apache Airflow DAGs monitored |
| **Detection** | 5 failure types classified via z-score drift detection and evidence-based anomaly fingerprinting across Airflow, CloudWatch & GitHub Actions signals |
| **Warehouse** | 5-table Glue-and-Athena warehouse driving SLA-risk forecasting and regulatory-deadline alerts |
| **Bugs Found** | Surfaced 4 latent bugs during build, including a silent API pagination cap that had been undercounting task runs |
| **Repository** | [github.com/goyalshubhi/sla-intelligence](https://github.com/goyalshubhi/sla-intelligence) |

</details>

<details>
<summary><b>🏥 Provider Intelligence Platform — Spark/Databricks Lakehouse</b></summary>
<br/>

Resolved duplicate and conflicting physician records across three real CMS government datasets using rule-based entity resolution.

| | |
|---|---|
| **Stack** | PySpark, Spark Declarative Pipelines, Databricks |
| **Data Sources** | 3 real CMS government datasets (NPI Registry, Open Payments, Part D) |
| **Entity Resolution** | Jaro-Winkler + NPI blocking, tuned to 0.98/0.98 last-name/first-name thresholds across 3 rounds of manual auto-match review to eliminate false provider merges |
| **History Tracking** | Full SCD Type 2 (Spark Declarative Pipelines AUTO CDC) behind tiered data-quality gates |
| **Bugs Found** | Debugged 8+ pipeline defects, including a silent truncation loading 2.5K rows where 78K were expected |
| **Repository** | [github.com/goyalshubhi/provider-intelligence-platform](https://github.com/goyalshubhi/provider-intelligence-platform) |

</details>

<details>
<summary><b>🔍 RAG Pipeline for Support Ticket Resolution</b></summary>
<br/>

Surfaces past resolutions for incoming support tickets through a 6-stage AWS-native RAG pipeline.

| | |
|---|---|
| **Stack** | AWS (S3, SQS, Lambda, Bedrock, OpenSearch, DynamoDB) |
| **Pipeline** | 6-stage: S3 ingest → SQS/DLQ buffering → Lambda processing → Bedrock Titan embeddings → OpenSearch Serverless vector search → DynamoDB lineage |
| **Security** | Least-privilege IAM, lineage-based deduplication |
| **Bugs Found** | Traced a chunking defect corrupting 22% of 500 test posts (chunks up to 41x oversized); capped output at exactly 512 characters |
| **Status** | Core pipeline logic validated against real data; end-to-end AWS integration pending a service-limit increase awaiting AWS approval |
| **Repository** | [github.com/goyalshubhi/rag-pipeline-aws](https://github.com/goyalshubhi/rag-pipeline-aws) |

</details>

<br/>

## 💼 Experience

**Big Data Analytics Intern** · Umbrella Infocare (a Noventiq company)
`May 2026 – June 2026`

- Contributed to data ingestion and transformation workflows across the team's AWS stack (S3, Glue, Athena), supporting cleaning, cataloging, and query preparation for client deliverables
- Self-initiated an AI-driven data-to-deck pipeline end-to-end via the BMAD-METHOD (agent personas for PM, Architect, Dev); shipped 13 user stories in one week as sole engineer
- Built a data-verification layer cross-checking every generated figure against source files pre-delivery, and integrated the Groq LLM API to auto-generate narrative business insights from processed data

`Python` `FastAPI` `React/TypeScript` `AWS S3` `AWS Glue` `AWS Athena` `Groq API`

<br/>

## 🏆 Leadership

<div align="center">

| Role | Organization | Impact |
|---|---|---|
| Events Head | Advanced Developers Group (ADG), VIT Vellore | Led planning and execution of 15+ technical events for 150+ students, increasing ADG club participation by 30% |

</div>

<br/>

## 📜 Certifications

<div align="center">

![AWS](https://img.shields.io/badge/AWS_Certified_Solutions_Architect_Associate-In_Progress-6D28D9?style=for-the-badge&logo=amazonaws&logoColor=white)
![HackerRank](https://img.shields.io/badge/HackerRank_SQL-Advanced-4C1D95?style=for-the-badge&logo=hackerrank&logoColor=white)

</div>

- **AWS Certified Solutions Architect – Associate**: Udemy prep complete, sitting for exam soon
- **HackerRank SQL (Advanced) Certificate**

<br/>

## 📊 GitHub Analytics

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=goyalshubhi&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=a78bfa&icon_color=8b5cf6&text_color=c9d1d9" width="48%"/>
<img src="https://streak-stats.demolab.com?user=goyalshubhi&theme=tokyonight&hide_border=true&background=0d1117&ring=8b5cf6&fire=a78bfa&currStreakLabel=a78bfa" width="48%"/>

<br/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=goyalshubhi&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=a78bfa&text_color=c9d1d9" width="48%"/>

</div>

<br/>

## 🏅 GitHub Trophies

<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=goyalshubhi&theme=algolia&no-frame=true&no-bg=true&column=7&margin-w=8&margin-h=8" width="100%"/>

</div>

<br/>

## 📈 Contribution Activity

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=goyalshubhi&theme=tokyo-night&hide_border=true&bg_color=0d1117&color=a78bfa&line=8b5cf6&point=c9d1d9" width="100%"/>

</div>

<br/>

## 🐍 Contribution Snake

<div align="center">

<img src="https://raw.githubusercontent.com/goyalshubhi/goyalshubhi/output/github-contribution-grid-snake-dark.svg" width="100%"/>

</div>

<br/>

## 🎯 Current Focus

```yaml
learning:
  - "AWS Solutions Architect Associate (SAA-C03) — final exam prep"
building:
  - "AWS-native RAG pipeline: end-to-end integration pending service-limit approval"
exploring:
  - "GenAI-assisted data engineering workflows (BMAD-METHOD, agentic dev)"
open_to:
  - "Data Engineering fresher roles, 2027 graduate"
```

<br/>

## 📬 Connect

<div align="center">

[![Gmail](https://img.shields.io/badge/-shubhangigoyal27@gmail.com-6D28D9?style=flat-square&logo=gmail&logoColor=white)](mailto:shubhangigoyal27@gmail.com)
[![LinkedIn](https://img.shields.io/badge/-shubhangi--goyal-7C3AED?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/shubhangi-goyal-4a148b26a)
[![GitHub](https://img.shields.io/badge/-goyalshubhi-5B21B6?style=flat-square&logo=github&logoColor=white)](https://github.com/goyalshubhi)

</div>

<br/>

<div align="center">

*"Pipelines that survive deep technical questioning, not ones that just look good on a slide."*

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=120&section=footer" width="100%"/>

</div>
