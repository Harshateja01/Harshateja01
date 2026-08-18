<div align="center">

# 👋 Hi, I'm Harsha Teja

### Product Analytics • Data Analytics • Machine Learning • Information Systems

**Turning data into decisions and models into usable products.**

M.S. Information Systems @ Stevens Institute of Technology | GPA: 3.8/4.0

<br>

![Python](https://img.shields.io/badge/Python-Data%20%26%20ML-blue?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-Analytics-blue?style=flat-square&logo=postgresql&logoColor=white)
![Tableau](https://img.shields.io/badge/Tableau-Visualization-orange?style=flat-square&logo=tableau&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-APIs-009688?style=flat-square&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-Deployment-2496ED?style=flat-square&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-Cloud-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)

</div>

---

## 👨‍💻 About Me

I'm an **Information Systems graduate from Stevens Institute of Technology** with professional experience spanning **software engineering, data analysis, business operations, and product-focused problem solving**.

I enjoy working at the intersection of **data, technology, and business** — turning messy datasets and ambiguous problems into measurable insights, analytical systems, and better product decisions.

My recent work includes building:

- An end-to-end **fraud detection and monitoring platform**
- A calibrated **credit risk decision-support system**
- A **Retrieval-Augmented Generation (RAG)** document intelligence application
- REST APIs, interactive dashboards, ML monitoring pipelines, and cloud-based applications

> 🎯 **Current focus:** Product Analyst • Data Analyst • Business Analyst • Technical Product • Applied Analytics

---

# 🚀 Featured Projects

## 🛡️ Fraud Detection Platform

### From 1.75M transactions → real-time fraud decisions

**Python • XGBoost • PostgreSQL • FastAPI • Streamlit • SHAP • Docker • GitHub Actions**

Built an end-to-end fraud detection platform covering the complete ML lifecycle — **data ingestion, leakage-safe feature engineering, model development, business optimization, explainability, serving, monitoring, testing, governance, and cloud deployment**.

### 📊 Results at a Glance

| Metric | Result |
|:---|---:|
| Transactions Processed | **1,754,155** |
| ROC-AUC | **0.8866** |
| PR-AUC | **0.6613** |
| Fraud Recall | **75.50%** |
| Precision@1,000 | **99.20%** |
| Production Threshold | **0.46** |
| Automated Tests | **14 passing** |

### 🔍 What I Built

- Designed and validated an ingestion pipeline for **1.75M+ transactions**
- Engineered customer velocity, spending, and terminal-risk features
- Implemented a **7-day fraud-label availability delay** to prevent target leakage
- Trained and evaluated an **XGBoost champion model**
- Compared supervised fraud detection against an **Isolation Forest** benchmark
- Optimized the production threshold using explicit false-positive and false-negative costs
- Evaluated **Precision@K and Recall@K** for limited investigation capacity
- Added global and transaction-level **SHAP explanations**
- Served predictions through a **FastAPI REST API**
- Built an investigator-facing **Streamlit dashboard**
- Implemented feature, prediction-score, and delayed-label performance monitoring
- Created unified model health states: `HEALTHY → MONITOR → REVIEW REQUIRED`
- Added **pytest + GitHub Actions CI**
- Containerized the system using **Docker**
- Deployed the API and dashboard to the cloud
- Documented model governance, monitoring policies, and known limitations

### 🏗️ Architecture

```text
Transaction Data
       │
       ▼
   PostgreSQL
       │
       ▼
Feature Engineering
       │
       ├── Customer Behavior
       └── Delayed Terminal Risk
       │
       ▼
   XGBoost Model
       │
       ├── Business Threshold Optimization
       ├── SHAP Explainability
       └── Model Monitoring
       │
       ▼
 Persisted Artifacts
       │
   ┌───┴────┐
   ▼        ▼
FastAPI  Streamlit
   │
   ▼
Cloud Deployment

CI/CD & Quality
      │
      └── Pytest → GitHub Actions → Docker
```

**Key takeaway:** This project focuses not only on predictive performance, but on how an ML model can be **evaluated, explained, deployed, tested, monitored, and governed as a complete system**.

---

## 💳 Credit Risk Forecasting & Decision Support

**Python • scikit-learn • SHAP • Streamlit • Probability Calibration**

Built an end-to-end credit risk decision-support system using approximately **30,000 customer records**, covering data validation, feature engineering, model comparison, calibration, threshold optimization, explainability, and deployment.

### 📈 Results

| Metric | Baseline | Improved |
|:---|---:|---:|
| ROC-AUC | 0.7474 | **0.7770** |
| PR-AUC | 0.5157 | **0.5558** |
| Brier Score | 0.1766 | **0.1361** |

### 🔍 What I Built

- Improved **ROC-AUC from 0.7474 → 0.7770**
- Improved **PR-AUC from 0.5157 → 0.5558**
- Achieved **0.7847 ± 0.0085 ROC-AUC** with 5-fold cross-validation
- Reduced Brier score from **0.1766 → 0.1361** through probability calibration
- Applied cost-sensitive threshold optimization
- Added global and customer-level **SHAP explainability**
- Built an interactive **Streamlit risk-assessment dashboard**

**Key takeaway:** Strong classification alone isn't enough for decision systems — **calibration, explainability, and decision thresholds matter too**.

---

## 🤖 Intelligent Document Q&A Platform

**Python • FastAPI • LangChain • FAISS • AWS • RAG**

Developed an AI-powered document intelligence application for asking natural-language questions across collections of unstructured documents.

### 🔍 What I Built

- Designed document ingestion and preprocessing workflows
- Implemented **Retrieval-Augmented Generation (RAG)**
- Generated embeddings for semantic document representation
- Used **FAISS vector search** for information retrieval
- Developed REST APIs with **FastAPI**
- Added validation and data-quality checks
- Integrated **AWS S3** for cloud-based storage
- Evaluated retrieval quality and investigated poor search results
- Documented architecture, technical workflows, and improvement opportunities

**Key takeaway:** Effective AI applications depend on the entire retrieval pipeline — not just the language model.

---

# 🧠 How I Think About Problems

I like working across the complete decision-making lifecycle:

```text
Business Problem
      ↓
Define Requirements
      ↓
Collect & Validate Data
      ↓
Analyze Behavior
      ↓
Build Model / Insight
      ↓
Translate Into Decision
      ↓
Deploy or Operationalize
      ↓
Measure Outcomes
      ↓
Improve
```

This allows me to work between **business stakeholders, analysts, engineers, and product teams** rather than treating analytics as an isolated technical task.

---

# 🛠️ Technical Toolkit

<table>
<tr>
<td valign="top" width="50%">

### 📊 Data & Analytics

`Python`  
`SQL`  
`Pandas`  
`NumPy`  
`Excel`  
`EDA`  
`Statistical Analysis`  
`Data Mining`

### 📈 Visualization & Reporting

`Tableau`  
`Power BI`  
`Matplotlib`  
`Dashboard Development`  
`Executive Reporting`  
`Excel VBA`

### 🗄️ Data & Databases

`PostgreSQL`  
`MySQL`  
`DynamoDB`  
`ETL`  
`Data Validation`  
`Data Transformation`  
`Query Optimization`

</td>

<td valign="top" width="50%">

### 🤖 Machine Learning & AI

`scikit-learn`  
`XGBoost`  
`SHAP`  
`LangChain`  
`FAISS`  
`RAG`  
`NLP`  
`Predictive Modeling`

### ⚙️ Engineering & Cloud

`FastAPI`  
`REST APIs`  
`Docker`  
`Git`  
`GitHub Actions`  
`AWS S3`  
`AWS Lambda`

### 📋 Product & Business

`Product Analysis`  
`Requirements Gathering`  
`User Stories`  
`Stakeholder Management`  
`Process Improvement`  
`Agile / Scrum`  
`Jira`  
`SDLC`

</td>
</tr>
</table>

---

# 💼 Professional Experience

## Software Engineer — SkillVertex

**Nov 2022 – Dec 2023 | India**

Worked across **technology, data, and business operations**, supporting reporting, operational analysis, troubleshooting, and product/process improvements.

- Analyzed operational datasets using **SQL and Excel** to support business decisions
- Performed data validation and reconciliation across multiple data sources
- Investigated recurring data-quality issues using structured **root-cause analysis**
- Collaborated with cross-functional stakeholders to understand requirements
- Supported product and process improvement initiatives
- Created workflow, validation, and process documentation
- Independently investigated and resolved operational issues while managing competing priorities

---

# 🎓 Education

## Stevens Institute of Technology

**Master of Science in Information Systems**

📊 **GPA:** 3.8 / 4.0  
🎓 **Graduated:** December 2025

---

# 🏆 Certification

## Goldman Sachs Software Engineering Virtual Experience

Focus areas:

`API Security` • `Risk Detection` • `Software Engineering`

---

# 💡 What I Bring

My strength is connecting **technical analysis with business outcomes**.

```text
              BUSINESS
                 ▲
                / \
               /   \
              /     \
             /       \
            /         \
           /           \
          ▼─────────────▼
        DATA       TECHNOLOGY
```

I can move between:

**SQL Analysis → Python Automation → Dashboards → Machine Learning → APIs → Product Requirements → Stakeholder Communication**

while keeping the original business question in focus.

---

# 📊 GitHub Activity

<div align="center">

![Harsha's GitHub Stats](https://github-readme-stats.vercel.app/api?username=Harshateja01&show_icons=true&hide_border=true&rank_icon=github)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Harshateja01&layout=compact&hide_border=true)

</div>

> GitHub language statistics represent repository code composition and are not a measure of overall proficiency.

---

# 🎯 Currently Exploring

I'm particularly interested in problems involving:

`Product Analytics` • `Fraud & Risk Analytics` • `Customer Behavior` • `Experimentation` • `Machine Learning` • `AI Products` • `Decision Systems` • `Data Visualization`

### Opportunities I'm Interested In

**Product Analyst • Data Analyst • Business Analyst • Technical Product • Applied Analytics**

I'm particularly interested in teams where analytics is used not just for reporting, but to **shape product decisions, improve systems, and drive measurable outcomes**.

---

# 📫 Let's Connect

I'm always interested in conversations around **analytics, product development, machine learning, and data-driven decision making**.

<div align="center">

### Let's turn data into better decisions.

💼 **LinkedIn:** [YOUR_LINKEDIN_URL](https://www.linkedin.com/in/harsha-teja-arikatla-1b4a761aa/)

📧 **Email:** harshateja565@gmail.com

</div>

---

<div align="center">

### Thanks for visiting! 👋

`Data → Insight → Decision → Impact`

</div>
