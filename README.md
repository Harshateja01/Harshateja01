# 👋 Hi, I'm Harsha Teja

### Product Analytics • Data Analytics • Machine Learning • Information Systems

> **Turning data into decisions and models into usable products.**

🎓 M.S. Information Systems — Stevens Institute of Technology  
📊 GPA: **3.8 / 4.0**  
💼 Software Engineering + Analytics experience  
🎯 Product Analyst • Data Analyst • Business Analyst • Technical Product

---

## 👨‍💻 About Me

I'm an **Information Systems graduate from Stevens Institute of Technology** with experience across **software engineering, data analytics, business operations, and product-focused problem solving**.

I enjoy working at the intersection of **data, technology, and business** — transforming complex datasets and ambiguous problems into measurable insights, analytical systems, and better decisions.

My work spans:

- 📊 Product and business analytics
- 🤖 Machine learning and predictive modeling
- 🧠 AI and Retrieval-Augmented Generation
- ⚙️ Data pipelines and REST APIs
- 📈 Interactive dashboards and reporting
- 🔍 Explainable AI and model monitoring
- ☁️ Cloud and containerized deployment

---

# 🚀 Featured Projects

## 🛡️ Fraud Detection Platform

### 1.75M transactions → real-time fraud decisions

**Python • XGBoost • PostgreSQL • FastAPI • Streamlit • SHAP • Docker • GitHub Actions**

Built an end-to-end fraud detection platform covering the complete machine learning lifecycle:

**Data Ingestion → Feature Engineering → Modeling → Business Optimization → Explainability → API → Dashboard → Monitoring → CI/CD → Cloud Deployment**

### 📊 Results

| Metric | Result |
|---|---:|
| Transactions Processed | **1,754,155** |
| ROC-AUC | **0.8866** |
| PR-AUC | **0.6613** |
| Fraud Recall | **75.50%** |
| Precision@1,000 | **99.20%** |
| Production Threshold | **0.46** |
| Automated Tests | **14 passing** |

### 🔍 What I Built

- Designed and validated an ingestion pipeline for **1.75M+ transactions**
- Engineered customer velocity, spending behavior, and terminal-risk features
- Implemented a **7-day fraud-label availability delay** to prevent target leakage
- Trained and evaluated an **XGBoost champion model**
- Benchmarked supervised detection against **Isolation Forest**
- Optimized the operating threshold using false-positive and false-negative business costs
- Evaluated **Precision@K and Recall@K** for limited investigator capacity
- Added global and transaction-level **SHAP explainability**
- Built a production-style **FastAPI scoring service**
- Developed an investigator-facing **Streamlit dashboard**
- Implemented feature drift monitoring using **Population Stability Index (PSI)**
- Monitored prediction-score distributions and delayed-label model performance
- Created unified model-health states:
  `HEALTHY → MONITOR → REVIEW REQUIRED`
- Added automated testing with **pytest**
- Integrated **GitHub Actions CI**
- Containerized the API and dashboard using **Docker**
- Deployed the application to the cloud
- Added model governance and monitoring documentation

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
              ┌──────────┴──────────┐
              ▼                     ▼
      Customer Behavior      Delayed Terminal
          Features             Risk Features
              │                     │
              └──────────┬──────────┘
                         ▼
                    XGBoost
                         │
            ┌────────────┼────────────┐
            ▼            ▼            ▼
        Threshold       SHAP       Monitoring
       Optimization  Explainability
            │
            ▼
       Model Artifacts
            │
       ┌────┴────┐
       ▼         ▼
    FastAPI   Streamlit
       │         │
       └────┬────┘
            ▼
      Cloud Deployment


Engineering Quality
       │
       ▼
Pytest → GitHub Actions → Docker
```

### 💡 Key Takeaway

This project goes beyond training a classifier. It demonstrates how a machine learning model can be **evaluated, explained, deployed, tested, monitored, and governed as an operational ML system**.

---

## 💳 Credit Risk Forecasting & Decision Support

**Python • scikit-learn • SHAP • Streamlit • Machine Learning**

Built an end-to-end credit risk decision-support system using approximately **30,000 customer records**, covering data validation, feature engineering, model comparison, probability calibration, threshold optimization, explainability, and deployment.

### 📈 Results

| Metric | Baseline | Improved |
|---|---:|---:|
| ROC-AUC | 0.7474 | **0.7770** |
| PR-AUC | 0.5157 | **0.5558** |
| Brier Score | 0.1766 | **0.1361** |

### Highlights

- Improved **ROC-AUC from 0.7474 → 0.7770**
- Improved **PR-AUC from 0.5157 → 0.5558**
- Achieved **0.7847 ± 0.0085 ROC-AUC** with 5-fold cross-validation
- Reduced Brier score from **0.1766 → 0.1361** through probability calibration
- Applied cost-sensitive threshold optimization
- Added global and customer-level **SHAP explanations**
- Developed an interactive **Streamlit risk-assessment dashboard**

### 💡 Key Takeaway

Strong classification performance alone isn't enough for decision systems — **probability calibration, explainability, and business thresholds matter too**.

---

## 🤖 Intelligent Document Q&A Platform

**Python • FastAPI • LangChain • FAISS • AWS • RAG**

Developed an AI-powered document intelligence platform that enables natural-language question answering across collections of unstructured documents.

### Highlights

- Designed document ingestion and preprocessing pipelines
- Implemented **Retrieval-Augmented Generation (RAG)**
- Generated embeddings for semantic document representation
- Used **FAISS vector search** for information retrieval
- Built REST APIs using **FastAPI**
- Added validation and data-quality checks
- Integrated **AWS S3** for cloud-based storage
- Evaluated retrieval quality and investigated search-quality issues
- Documented system architecture and technical workflows

### 💡 Key Takeaway

Reliable AI applications depend on the complete **data → retrieval → context → generation** pipeline, not just the language model.

---

# 🧠 How I Approach Problems

I like working across the full decision-making lifecycle:

```text
Business Problem
      ↓
Requirements
      ↓
Data Collection & Validation
      ↓
Analysis
      ↓
Model / Insight
      ↓
Business Decision
      ↓
Operationalization
      ↓
Measurement
      ↓
Iteration
```

This allows me to work across **business, analytics, engineering, and product teams** rather than treating analytics as an isolated technical activity.

---

# 🛠️ Technical Toolkit

### 📊 Data & Analytics

`Python` `SQL` `Pandas` `NumPy` `Excel` `EDA` `Statistical Analysis` `Data Mining`

### 📈 Visualization & Reporting

`Tableau` `Power BI` `Matplotlib` `Streamlit` `Dashboard Development` `Executive Reporting` `Excel VBA`

### 🗄️ Databases & Data Engineering

`PostgreSQL` `MySQL` `DynamoDB` `ETL` `Data Transformation` `Data Validation` `Query Optimization`

### 🤖 Machine Learning & AI

`scikit-learn` `XGBoost` `SHAP` `LangChain` `FAISS` `RAG` `NLP` `Predictive Modeling` `Anomaly Detection`

### ⚙️ Engineering & Cloud

`FastAPI` `REST APIs` `Docker` `Git` `GitHub Actions` `AWS S3` `AWS Lambda` `pytest`

### 📋 Product & Business

`Product Analysis` `Requirements Gathering` `User Stories` `Stakeholder Management` `Process Improvement` `Product Documentation` `Agile` `Scrum` `Jira` `SDLC`

---

# 💼 Professional Experience

## Software Engineer — SkillVertex

**Nov 2022 – Dec 2023 | India**

Worked at the intersection of **technology, data, and business operations**, supporting analytics, reporting, troubleshooting, and product/process improvements.

- Analyzed operational datasets using **SQL and Excel** to support reporting and business decisions
- Performed data validation and reconciliation across multiple data sources
- Investigated recurring data-quality issues through structured **root-cause analysis**
- Collaborated with cross-functional stakeholders to gather and understand requirements
- Supported product and process-improvement initiatives
- Created workflow, validation, and process documentation
- Independently investigated and resolved operational issues while managing multiple priorities

---

# 🎓 Education

## Stevens Institute of Technology

**Master of Science in Information Systems**

**GPA:** 3.8 / 4.0  
**Graduated:** December 2025

---

# 🏆 Certification

### Goldman Sachs Software Engineering Virtual Experience

`API Security` • `Risk Detection` • `Software Engineering`

---

# 💡 What I Bring

I combine **business understanding, analytical thinking, and technical execution**.

```text
Business Question
       ↓
Requirements
       ↓
Data
       ↓
Analysis
       ↓
Insight / Model
       ↓
Product Decision
       ↓
Measurable Impact
```

My background allows me to move between:

**SQL Analysis → Python → Dashboards → Machine Learning → APIs → Product Requirements → Stakeholder Communication**

while keeping the underlying **business problem** at the center.

---

# 📊 GitHub Activity

![Harsha's GitHub Stats](https://github-readme-stats.vercel.app/api?username=Harshateja01&show_icons=true&hide_border=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Harshateja01&layout=compact&hide_border=true)

> GitHub language statistics represent repository code composition rather than overall technical proficiency.

---

# 🔭 Currently Exploring

I'm particularly interested in problems involving:

`Product Analytics` • `Fraud & Risk Analytics` • `Customer Behavior` • `Experimentation` • `Machine Learning` • `AI Products` • `Decision Systems` • `Data Visualization`

---

# 🎯 Opportunities I'm Interested In

I'm currently exploring opportunities in:

### Product Analyst • Data Analyst • Business Analyst • Technical Product • Applied Analytics

I'm particularly interested in teams where data is used not only for reporting, but to **shape product decisions, improve systems, understand users, and drive measurable outcomes**.

---

# 📫 Let's Connect

I'm always interested in conversations around **analytics, product development, machine learning, AI, and data-driven decision making**.

**LinkedIn:** https://www.linkedin.com/in/harsha-teja-arikatla-1b4a761aa/  
**Email:** harshateja565@gmail.com

---

### Thanks for visiting! 👋

**Data → Insight → Decision → Impact**
