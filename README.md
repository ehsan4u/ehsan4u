👋 Hi, I'm Muhammad Ehsan – a Senior Data Engineering Consultant with deep experience in:
✅ Azure Cloud (ADF, ADLS, Synapse)
✅ Databricks (Delta Lake, PySpark)
✅ Data Governance & CI/CD in enterprise & public sector
📊 Explore my latest project: [Canada Open Data Pipeline](https://github.com/ehsanullah/canada-open-data-pipeline)


LEADERSHIP
Cross-functional team management, agile project delivery, and stakeholder collaboration

SKILLS
Big Data Tools: Apache Spark, Hadoop (CDP/CDH/HDP) , Hive, Kafka, Airflow, Apache NIFI , DBT,   Databricks (Delta Lake), Spark, Hortonworks (Ambari), Pig, Flume, Sqoop, TDCH, Knox, Kerberos, Ranger
Data Modeling: Erwin Data Modeler
Cloud Data Platforms: GCP (BigQuery, Dataflow, Dataproc, Google Cloud Storage), Azure (Azure Data Lake Storage (ADLS), Databricks, Azure Synapse, Data Factory), AWS (Databricks, S3, Glue, Redshift), Snowflake 
PostgreSQL, MySQL, SQL Server, Redshift
Data Engineering: ETL/ELT pipelines, data lake/Lakehouse architectures, real-time data processing
Data Governance & Cataloging: Data quality frameworks, metadata management, data lineage, and compliance (GDPR, SOX), Unity Catalog (Metadata & Governance), Microsoft Purview, Dataplex
Machine Learning & AI: Predictive modeling, MLOps, TensorFlow, PyTorch, Scikit-learn
Programming: Python, PySpark, SQL, Bash, Java, C#
Data Visualization: Power BI, Tableau, SAS
Automation & DevOps: Ansible, Puppet, Docker, Kubernetes, CICD
Schedulers: Informatica, Control-M, Autosys, Cloud Composer
CERTIFICATIONS
Alteryx Certified – Designer CORE 
Alteryx Server Administrator
Tableau Data Analyst
Tableau Server Associate
Data Engineer Associate (Databricks)
Oracle Big Data Appliance – Administration
Cloudera Certified Data Analyst (CCA 159)
Cloudera Certified Hadoop & Spark Administrator (CCA 131)
PMP Certified (PMI ID: 6307991)
Certified Ethical Hacker (2013)
Six Sigma Green Belt & Yellow Belt
CCISP (2014)
ITIL Foundation v3

<!--
**ehsan4u/ehsan4u** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

# Muhammad Ehsan — Data & AI Project Portfolio
### Senior Manager, Business Intelligence, Data Engineering & Advanced Analytics | Qatar Airways

> 20+ years delivering enterprise-scale data platforms, AI/ML solutions, and digital transformation programmes across aviation, manufacturing, government, and telecommunications.
>
> 📧 ehsan4u@gmail.com · 📞 +1 571 554 4040 · [LinkedIn](https://linkedin.com/in/ehsanullah)

---

## Table of Contents
- [MRO & Supply Chain](#-mro--supply-chain)
- [Finance](#-finance)
- [Customers](#-customers)
- [Cargo](#-cargo)
- [HR](#-hr)
- [Qatar Executive](#-qatar-executive-private-charter)
- [Transformation](#-transformation)
- [Pratt & Whitney](#-pratt--whitney)
- [Federal Government of Canada](#-federal-government-of-canada)

---

## 🛩️ MRO & Supply Chain

---

### MRO Engineering Intelligence Platform
**Organization:** Qatar Airways · **Timeframe:** 2023–Present

**Overview:**
Enterprise AI platform that transforms global aviation maintenance, repair, and overhaul (MRO) data into quantified financial insights for C-suite and operational leadership. Spans Engineering, MRO, Supply Chain, and Finance domains.

**Technical Architecture:**
- Google Cloud Vertex AI as the ML serving and orchestration layer
- Gemini LLMs (1.5 Pro / Flash) for multi-modal reasoning and executive report generation
- Vector search (Vertex AI Matching Engine) for semantic retrieval across maintenance documentation
- BigQuery as the analytical data warehouse with Dataplex governance overlay
- Airflow + dbt for data pipeline orchestration and transformation
- Real-time dashboards via Looker Studio and Tableau for executive consumption

**Key Outcomes:**
- Provides executive leadership with proactive, data-driven insights across global MRO operations
- Quantifies financial impact of maintenance events, supplier performance, and fleet availability trends
- Reduces time from data to decision for engineering and supply chain leadership

**Skills:** `Vertex AI` `Gemini LLMs` `BigQuery` `Vector Search` `Airflow` `dbt` `Tableau` `Data Architecture` `Generative AI`

---

### ClearAI — Technical Operations Intelligence Platform
**Organization:** Qatar Airways · **Timeframe:** 2023–Present

**Overview:**
Enterprise AI platform leveraging NLP, semantic embeddings, machine learning, and Generative AI to cluster, analyze, and optimize aircraft maintenance task cards — enabling data-driven engineering decision-making at scale.

**Technical Architecture:**
- Azure OpenAI (GPT-4) for task card analysis and natural language generation
- Sentence transformer models and FAISS/pgvector for semantic embedding and clustering
- Unsupervised ML (K-Means, HDBSCAN) for maintenance task clustering
- Python (spaCy, Hugging Face Transformers) for NLP pipeline
- Azure Databricks as the compute and ML platform
- Azure Data Lake Storage Gen2 for raw and curated data layers

**Key Outcomes:**
- Identified 15–20% potential reduction in maintenance man-hours through task consolidation and optimization
- Improved aircraft availability by surfacing redundant and inefficient maintenance procedures
- Automated engineering decision support, reducing reliance on manual expert review

**Skills:** `Azure OpenAI` `NLP` `Semantic Embeddings` `Clustering` `Databricks` `Python` `ADLS Gen2` `Generative AI` `MLOps`

---

### TRAX → AMOS Migration Data Strategy
**Organization:** Qatar Airways · **Timeframe:** 2024–Present

**Overview:**
End-to-end data strategy and pipeline architecture for a mission-critical MRO system migration from TRAX to AMOS, covering Line Maintenance, Heavy Maintenance, and Supply Chain operational data.

**Technical Architecture:**
- Data discovery and profiling across TRAX operational database schemas
- Custom ETL pipelines (Python, Airflow) for schema-level transformation and mapping
- Automated data validation and reconciliation frameworks (row counts, business rule checks, referential integrity)
- Staging environment on GCP for parallel validation before cutover
- Data lineage documentation and migration audit trail in BigQuery

**Key Outcomes:**
- Zero-loss data continuity across Line Maintenance, Heavy Maintenance, and Supply Chain
- Validated migration readiness through automated reconciliation reducing cutover risk
- Established reusable migration framework applicable to future system transitions

**Skills:** `ETL/ELT` `Airflow` `Python` `GCP BigQuery` `Data Migration` `Data Validation` `MRO Systems` `Data Architecture`

---

### Predictive Maintenance & Inventory Forecasting
**Organization:** Qatar Airways · **Timeframe:** 2023–Present

**Overview:**
ML-based predictive maintenance scheduling and inventory forecasting platform to reduce AOG (aircraft-on-ground) risk and optimize MRO stock levels across Qatar Airways' global fleet.

**Technical Architecture:**
- Time-series forecasting models (Prophet, LSTM) for parts demand prediction
- Survival analysis for component failure probability estimation
- BigQuery ML for scalable model training and batch inference
- Airflow-orchestrated scoring pipelines running daily across the fleet
- Power BI dashboards surfacing AOG risk scores and reorder recommendations to MRO planners

**Key Outcomes:**
- Reduced unplanned AOG events through proactive parts availability alerts
- Optimized inventory buffer levels, reducing carrying costs without compromising availability
- Embedded ML-driven recommendations into MRO planner daily workflows

**Skills:** `Time Series Forecasting` `Predictive Maintenance` `BigQuery ML` `Python` `Prophet` `LSTM` `Power BI` `Airflow`

---

## 💼 Finance

---

### Finance Data Warehouse Migration & Analytics Suite
**Organization:** Qatar Airways · **Timeframe:** 2023–Present

**Overview:**
Strategic migration of on-premise finance data warehouses to Google BigQuery and Azure Synapse, paired with the development of 14+ analytical data products spanning Finance, Treasury, Global Business Solutions (GBS), and Supply Chain.

**Technical Architecture:**
- BigQuery as the primary analytical DW; Azure Synapse for Finance-specific workloads
- dbt (data build tool) for curated data modeling, lineage, testing, and documentation
- Airflow on Cloud Composer for pipeline orchestration
- GCS + Pub/Sub + Cloud Functions for real-time structured/semi-structured ingestion
- Dataplex for data catalog, quality scoring, and governance
- Tableau and Power BI for executive and operational dashboards

**Key Outcomes:**
- 45% query performance improvement post-migration
- 14+ production analytical data products deployed
- 5M+ records processed daily at 99.9% accuracy
- Full data lineage, automated testing, and CI/CD validation established across all dbt models

**Skills:** `BigQuery` `Azure Synapse` `dbt` `Airflow` `GCS` `Pub/Sub` `Dataplex` `Tableau` `Power BI` `Data Modeling` `Cloud Migration`

---

### Treasury & Exposure Monitoring Platform
**Organization:** Qatar Airways · **Timeframe:** 2023–Present

**Overview:**
Real-time treasury analytics platform providing FX exposure monitoring, liquidity position dashboards, and financial risk reporting for the Treasury team and CFO office.

**Technical Architecture:**
- Real-time ingestion of treasury system feeds via Pub/Sub and Cloud Functions into BigQuery
- Financial risk models (VaR, sensitivity analysis) implemented in Python and BigQuery ML
- Looker Studio and Tableau dashboards for live CFO and Treasury team consumption
- Row-level security and dynamic data masking for sensitive financial data

**Key Outcomes:**
- CFO office now has real-time FX exposure visibility vs. end-of-day batch reports
- Automated treasury risk alerts reduce manual monitoring workload
- Compliant with SOX and internal audit requirements

**Skills:** `BigQuery` `Pub/Sub` `Python` `Tableau` `Looker` `Financial Analytics` `Data Security` `SOX Compliance`

---

### Finance Transformation — Continuous Delivery Analytics
**Organization:** Qatar Airways · **Timeframe:** 2024–Present

**Overview:**
Data readiness assessments, benefits realization tracking, and DMAIC-based process improvement dashboards supporting the Finance Transformation & Continuous Delivery programme.

**Key Outcomes:**
- Quantified benefits realization across transformation workstreams
- DMAIC charter and measurement framework embedded in programme governance
- Executive progress dashboards enabling data-driven programme steering

**Skills:** `DMAIC` `Lean Six Sigma` `Benefits Realization` `Programme Analytics` `Power BI`

---

## 👥 Customers

---

### Customer Analytics Platform
**Organization:** Qatar Airways · **Timeframe:** 2023–Present

**Overview:**
End-to-end customer analytics platform enabling segmentation, churn prediction, loyalty programme optimization, and NPS measurement across millions of Privilege Club members.

**Technical Architecture:**
- Customer 360 data model in BigQuery aggregating booking, loyalty, service, and contact centre data
- Segmentation via RFM analysis and K-Means clustering
- Churn prediction model (XGBoost, logistic regression) with Airflow-scheduled batch scoring
- NPS pipeline from survey data ingestion to trend analysis dashboards
- Looker dashboards for CX and Marketing teams; ML model monitoring via Vertex AI

**Key Outcomes:**
- Enabled targeted personalization campaigns based on ML-driven segmentation
- Churn model deployed in CRM to trigger proactive retention interventions
- NPS tracking automated from manual spreadsheets to real-time dashboard

**Skills:** `BigQuery` `Python` `XGBoost` `Clustering` `Vertex AI` `Looker` `Customer Analytics` `CRM Integration`

---

## 📦 Cargo

---

### Cargo BI Suite
**Organization:** Qatar Airways · **Timeframe:** 2023–Present

**Overview:**
Business intelligence platform for Qatar Airways Cargo operations, one of the world's largest cargo carriers. Covers capacity utilization, yield optimization, and route performance analytics.

**Technical Architecture:**
- Cargo operational data integrated from reservation and weight/balance systems into BigQuery
- Yield optimization models using regression and optimization algorithms
- Capacity utilization dashboards with real-time load factor monitoring per route
- Power BI reports distributed to Cargo Revenue Management and Operations teams

**Key Outcomes:**
- Improved load factor visibility enabling dynamic yield adjustments
- Route profitability analytics embedded into Revenue Management daily workflows
- Reduced manual reporting effort by automating 8+ weekly Cargo reports

**Skills:** `BigQuery` `Python` `Power BI` `Revenue Analytics` `Capacity Planning` `ETL/ELT`

---

## 🧑‍💼 HR

---

### PeopleX — Agentic HR Copilot
**Organization:** Qatar Airways · **Timeframe:** 2024–Present

**Overview:**
Agentic AI copilot built on Google Vertex AI and Gemini, enabling HR leadership and business managers to have conversational, natural-language access to workforce analytics, headcount planning data, and HR KPIs — without needing to navigate BI dashboards.

**Technical Architecture:**
- Vertex AI Agent Builder with Gemini 1.5 Pro as the reasoning engine
- RAG architecture: HR knowledge base vectorized in Vertex AI Matching Engine
- BigQuery as the HR data warehouse (headcount, attrition, compensation, recruitment)
- Tool use / function calling for live BigQuery query execution from natural language
- Secure access control: role-based query scoping to prevent data leakage
- Integrated with existing HR systems via API connectors

**Key Outcomes:**
- HR leadership can query headcount, attrition, and recruitment pipeline conversationally
- Reduced dependency on static monthly HR reports — self-serve analytics for business managers
- Foundation for expanding agentic capabilities across the HR function

**Skills:** `Vertex AI` `Gemini` `RAG` `Agentic AI` `BigQuery` `Vector Search` `Function Calling` `HR Analytics` `NLP`

---

## 🚁 Qatar Executive (Private Charter)

---

### Qatar Executive Analytics Platform
**Organization:** Qatar Airways · **Timeframe:** 2023–Present

**Overview:**
Analytics platform for Qatar Executive's private jet charter operations, covering fleet utilization, revenue-per-flight analytics, and charter demand forecasting.

**Key Outcomes:**
- Fleet utilization dashboards enable proactive aircraft scheduling and availability management
- Revenue-per-flight analytics surface profitability by route, aircraft type, and client segment
- Demand forecasting models improve charter sales pipeline visibility

**Skills:** `BigQuery` `Tableau` `Python` `Forecasting` `Revenue Analytics`

---

## 🔄 Transformation

---

### Clarizen → Asana Migration & Adoption Analytics
**Organization:** Qatar Airways · **Timeframe:** 2024–Present

**Overview:**
Full project portfolio data migration from Clarizen to Asana, combined with an adoption analytics platform to track onboarding velocity and usage across business units for the enterprise PMO.

**Technical Architecture:**
- Clarizen API extraction → data transformation → Asana API loading pipelines (Python, Airflow)
- Data validation framework ensuring portfolio data integrity post-migration
- Asana usage analytics via API: adoption rate, active users, task completion metrics by business unit
- Power BI adoption dashboard for PMO leadership

**Key Outcomes:**
- Successful migration of active project portfolio with zero data loss
- PMO leadership has real-time visibility into Asana adoption across BUs
- Enabled data-driven interventions for low-adoption teams

**Skills:** `Python` `Airflow` `REST APIs` `Power BI` `Data Migration` `PMO Analytics`

---

## ✈️ Pratt & Whitney

---

### AI Evolution Lab
**Organization:** Pratt & Whitney – Raytheon Technologies · **Timeframe:** 2020–2023

**Overview:**
Established and led Pratt & Whitney's enterprise AI capability from the ground up — a dedicated experimentation and production ML environment for predictive maintenance, jet engine reliability analytics, and operational intelligence.

**Technical Architecture:**
- AWS (SageMaker, S3, Lambda, Kinesis) as primary ML platform
- Azure Databricks for large-scale Spark-based feature engineering
- MLOps framework: model versioning (MLflow), automated retraining pipelines, drift monitoring
- REST APIs for model serving into engineering and maintenance planning systems
- Feature store for cross-team reuse of engineered ML features

**Key Outcomes:**
- Production ML models for predictive maintenance reduced unplanned maintenance events
- Established organization-wide MLOps standards and governance adopted across BUs
- Accelerated time-to-model from months to weeks through reusable experimentation frameworks

**Skills:** `AWS SageMaker` `Databricks` `MLflow` `MLOps` `Predictive Maintenance` `Python` `PySpark` `REST APIs`

---

### Cloudera → Databricks Migration
**Organization:** Pratt & Whitney – Raytheon Technologies · **Timeframe:** 2021–2022

**Overview:**
Migration of the enterprise Cloudera (CDH/HDP) data lake to Databricks Delta Lake — modernizing the data platform for scalability, performance, and ML readiness.

**Key Outcomes:**
- Improved data processing efficiency and eliminated Cloudera licensing costs
- Delta Lake ACID transactions and time-travel enabled reliable ML feature engineering
- Unity Catalog established as the enterprise data governance layer post-migration

**Skills:** `Databricks` `Delta Lake` `Unity Catalog` `Cloudera` `Spark` `dbt` `Data Governance`

---

### SAP ERP Data Integration Pipelines
**Organization:** Pratt & Whitney – Raytheon Technologies · **Timeframe:** 2020–2023

**Overview:**
Automated ETL pipelines sourcing Finance, Inventory, and HR data from SAP ERP modules into cloud data warehouses, eliminating manual extraction and enabling analytics at scale.

**Key Outcomes:**
- 60% reduction in manual data extraction effort
- Full audit trail and data lineage for all SAP-sourced datasets
- Enabled self-serve analytics for Finance, Supply Chain, and HR teams

**Skills:** `SAP Connectors` `Python` `SQL` `Airflow` `dbt` `Databricks` `Cloud Data Warehousing`

---

## 🏛️ Federal Government of Canada

---

### Government Analytics Platform
**Organization:** Federal Government of Canada · **Timeframe:** 2013–2019

**Overview:**
Designed and delivered a centralized data lake and analytics capability serving multiple federal departments — enabling cloud-based data sharing, advanced analytics, and large-scale data governance at public sector scale.

**Technical Architecture:**
- Hadoop (Cloudera CDH) as the core data lake platform; Cloudera Manager for cluster administration
- Apache Spark and Airflow for large-scale batch and real-time ETL processing
- Azure Data Factory pipelines for on-prem to Azure Blob / Azure Databricks migration
- Azure Batch for custom data transformation at scale
- Oozie for legacy workflow orchestration
- Python/SQL automation scripts saving ~20 hours/month of manual effort

**Key Outcomes:**
- Centralized data access across multiple government departments on a single governed platform
- Cloud migration foundation established for future Azure-based analytics workloads
- Deputy Minister Award of Excellence (2021) for outstanding contribution to Government data initiatives

**Skills:** `Hadoop` `Cloudera` `Spark` `Airflow` `Azure Data Factory` `Azure Databricks` `Python` `SQL` `Data Governance`

---

### Hadoop Security Implementation
**Organization:** Federal Government of Canada · **Timeframe:** 2013–2019

**Overview:**
End-to-end Hadoop cluster security across a multi-department government data environment — implementing authentication, authorization, encryption, and identity integration.

**Technical Architecture:**
- Kerberos for cluster-wide authentication
- Apache Knox as the API gateway and perimeter security layer
- Apache Ranger for fine-grained authorization policies (HDFS, Hive, HBase)
- Active Directory integration for identity federation across government departments
- SSL/TLS encryption for data in transit; HDFS encryption zones for data at rest

**Key Outcomes:**
- Enterprise-grade security posture across sensitive government data lake
- Compliant with Government of Canada Protected B data standards
- Established security patterns reused across multiple subsequent department onboardings

**Skills:** `Kerberos` `Knox` `Ranger` `Active Directory` `Hadoop Security` `Data Encryption` `GDPR` `Compliance`

---

## 🏅 Certifications

| Domain | Certifications |
|--------|----------------|
| Security & PM | CISSP · CEH · PMP (PMI ID: 6307991) · ITIL v3 |
| Data & Cloud | Databricks Data Engineer Associate · GCP Professional Cloud Architect · Cloudera CCA-159 · CCA-131 · Oracle Big Data |
| Analytics & BI | Tableau Data Analyst · Tableau Server Associate · Alteryx Designer Core · Alteryx Server Admin |
| Process | Lean Six Sigma Green Belt · Yellow Belt |

---

## 🛠️ Technology Stack

| Layer | Technologies |
|-------|-------------|
| Cloud | GCP (BigQuery, Vertex AI, Dataflow, GCS, Pub/Sub, Cloud Functions) · Azure (Synapse, ADF, ADLS, Databricks) · AWS (S3, Glue, SageMaker, Kinesis, Lambda, Redshift) |
| Data Engineering | Apache Spark · Airflow · dbt · Databricks (Delta Lake, Unity Catalog) · Kafka · NIFI · Informatica · Control-M |
| AI / ML | Gemini · Azure OpenAI · Vertex AI · MLflow · Hugging Face · scikit-learn · TensorFlow · PyTorch · FAISS · LangChain |
| BI & Viz | Power BI · Tableau · Looker Studio · Alteryx |
| Programming | Python · PySpark · SQL · Bash · Terraform · CloudFormation |
| Governance | Dataplex · Microsoft Purview · Unity Catalog · Apache Ranger · Kerberos |

---

*Last updated: June 2026*
