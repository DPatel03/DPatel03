<div align="center">

# Deep Patel

**Data engineer · Software engineer · Boston, MA**

MS in Data Science at Boston University, finishing December 2026

[![Portfolio](https://img.shields.io/badge/Portfolio-deep--portfolio--web.vercel.app-111827?style=flat-square)](https://deep-portfolio-web.vercel.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-dpatel06-0A66C2?style=flat-square)](https://www.linkedin.com/in/dpatel06/)
![Open to](https://img.shields.io/badge/Open_to-2027_new_grad_roles-2ea44f?style=flat-square)

</div>

<br>

## About me

I did my undergrad in computer science at CUNY Queens College, mostly because I like building things people end up relying on. These days I'm finishing a master's in data science at BU, and data engineering is where I've landed. It changed how I think about reliability, throughput, and what happens to a system under load.

I like owning a problem end to end: the frontend, the backend, the database, and the data moving through all of it.

Right now I'm a Technical Product Manager at BU Spark!, running delivery on a few client software projects. I'm looking for 2027 new grad roles in **data engineering**, **backend engineering**, or **applied ML**, in Boston, NYC, or remote.

<br>

## Projects

**[DataSentinel](https://github.com/DPatel03/DataSentinel)**<br>
Every data pipeline gets bad records eventually. This one checks NYC taxi trips streaming through Kafka against a versioned data contract and sends failures to a dead-letter queue. From there, LLM agents decide whether each record can be repaired, is a real anomaly, or needs a human. Prompt versions are tracked in Postgres and roll back automatically if accuracy drops.<br>
<sub>Kafka · PySpark · Great Expectations · TimescaleDB · Pydantic · Docker</sub>

<br>

**[Gateway Cities Dashboard](https://github.com/BU-Spark/dd4g-gbh-gateway-cites)** · [live demo](https://dd4g-gatewayscities.up.railway.app/)<br>
A dashboard for journalists and researchers tracking how the foreign-born population has changed across Massachusetts' 26 Gateway Cities (Census ACS data, 2012 to 2024). It has maps, trend charts, and a chatbot that answers plain-English questions with Gemini on top of the real numbers. Built through BU Spark!<br>
<sub>React · Vite · Flask · Pandas / Parquet · Gemini</sub>

<br>

**Epidemic Engine** · private course repo<br>
A health-event streaming platform on OpenShift. Kafka offsets are checkpointed, so a crashed consumer can replay without losing or double-counting anything, and PySpark jobs flag outbreak surges with rolling z-scores.<br>
<sub>Kafka · PySpark · OpenShift · Tekton · TimescaleDB · Flask</sub>

<br>

**[Credit Risk Prediction](https://github.com/DPatel03/credit-risk-prediction-and-decisioning)**<br>
Takes raw HMDA mortgage data through feature engineering and a calibrated logistic regression, then turns the probabilities into approve / review / reject decisions. Every prediction and decision is logged to PostgreSQL so it can be audited later.<br>
<sub>Python · scikit-learn · PostgreSQL</sub>

<br>

**[Justice Lens](https://github.com/aadpaguio/civichacks_justice_lens)**<br>
A Streamlit app for digging through Boston police misconduct records. The datasets don't share a key, so officers are linked with fuzzy name matching, and dozens of inconsistent allegation labels are cleaned up so repeat complaints actually show.<br>
<sub>Python · Streamlit · Pandas · Plotly</sub>

<br>

**[Sales Performance Dashboard](https://github.com/DPatel03/sales-performance-analysis-dashboard)**<br>
A small end-to-end analytics project: generate synthetic sales data, load it into a SQLite warehouse, analyze it in SQL, and explore the KPIs in Streamlit.<br>
<sub>Python · SQL · Streamlit</sub>

<br>

## Where I've worked

**Technical Product Manager, BU Spark!** · Sep 2026 to now<br>
I turn client briefs into milestones and sprint plans for student engineering teams and run their weekly technical reviews. Most recently I scoped the rebuild of a Boston heating-system map covering nearly 100K parcels.

**Software Engineer Intern, BU Spark!** · May to Jul 2026<br>
Built a web platform for the Massachusetts Department of Early Education and Care that replaced phone and spreadsheet registration for 7 regional child care agencies. Each agency sees only its own records, and state administrators see everything. (Next.js, TypeScript, PostgreSQL, Prisma, Clerk)

**Software Engineer, Prama** · Jan to Aug 2025<br>
Shipped a role-based React and Spring Boot dashboard for tracking engineering projects. Added indexes and a Redis cache that cut query latency by 35% in load tests. Also traced endpoint failures (about 12%) to token refresh, and retry with backoff brought them under 0.5%.

<br>

## What I work with

**Languages**<br>
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white) ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

**Data & streaming**<br>
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white) ![Spark](https://img.shields.io/badge/PySpark-E25A1C?style=flat-square&logo=apachespark&logoColor=white) ![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white) ![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white) ![Great Expectations](https://img.shields.io/badge/Great_Expectations-FF6310?style=flat-square)

**Databases**<br>
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white) ![TimescaleDB](https://img.shields.io/badge/TimescaleDB-FDB515?style=flat-square&logo=timescale&logoColor=black)

**Backend & web**<br>
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white) ![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white) ![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white) ![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)

**ML & AI**<br>
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white) ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white) ![RAG](https://img.shields.io/badge/RAG-pipelines-6B7280?style=flat-square) ![Gemini](https://img.shields.io/badge/Gemini_API-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)

**Cloud & infra**<br>
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white) ![OpenShift](https://img.shields.io/badge/OpenShift-EE0000?style=flat-square&logo=redhatopenshift&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)


<br>

<div align="center">

The fastest way to reach me is [LinkedIn](https://www.linkedin.com/in/dpatel06/).

</div>
