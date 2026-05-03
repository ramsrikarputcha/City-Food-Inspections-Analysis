# City-Food-Inspections-Analysis
---

## 📌 Summary  

🚀 **End-to-End Data Engineering & Analytics Platform** built to process large-scale, real-world structured datasets and deliver KPI-driven insights.

This project demonstrates:
- **Data Engineering**: Cloud ETL pipelines, warehouse design, dimensional modeling  
- **Data Analytics**: Data profiling, cleansing, normalization, scoring, and metric derivation  
- **Business Intelligence**: Interactive dashboards and executive reporting using Power BI  

The solution is intentionally **domain-agnostic** and reusable across industries such as technology, operations, compliance, and business analytics.

---

## 📂 Datasets  

- **Dataset A**: ~300K records with mixed categorical and numerical attributes  
- **Dataset B**: ~80K records with wide schemas and semi-structured fields  

These datasets simulate common real-world challenges such as inconsistent schemas, nested fields, and data quality issues.

---

## 🛠️ Tech Stack  

| Category               | Tools Used |
|------------------------|------------|
| Data Profiling         | YData, Alteryx |
| ETL & Pipelines        | Azure Data Factory, Snowflake, Databricks, SQL |
| Data Modeling          | ER/Studio – Dimensional (Star Schema) |
| Visualization          | Power BI – KPI Dashboards, Interactive Filters |
| Scripting & Cleaning   | Python, Regex, SQL |

---

## 🧼 Data Engineering Process  

### 🧱 Medallion Architecture  

Implemented a **Bronze → Silver → Gold** architecture using Snowflake, Databricks, and Azure Data Factory.

- **Bronze**: Raw data ingestion  
- **Silver**: Data cleaning, parsing, and standardization  
- **Gold**: Analytics-ready dimensional models optimized for BI and reporting  

---

### 🔄 ETL Highlights  

- Cleaned and transformed wide, high-column datasets using Alteryx workflows  
- Parsed nested and delimited fields into normalized structures  
- Derived standardized outcome metrics and categorical classifications  
- Applied regex-based transformations to improve schema consistency  
- Converted denormalized inputs into analytics-ready relational formats  

---

## 🧾 Data Warehouse Design  

🧠 **Grain**: One row per event per entity per date  

### 📌 Dimension Tables  
- DIM_LOCATION  
- DIM_ENTITY  
- DIM_EVENT  
- DIM_RESULT  
- DIM_CATEGORY  

### 📌 Fact Table  
- FACT_EVENTS – captures measurable outcomes and joins all dimension keys  

All tables are orchestrated and loaded via Azure Data Factory pipelines.

---

## 📈 Key Skills Demonstrated  

- End-to-end cloud data pipeline development  
- Dimensional modeling and analytics engineering  
- Advanced data cleansing and normalization  
- ETL orchestration with Azure Data Factory  
- KPI design and interactive BI reporting  

---

## 🎯 What This Project Demonstrates  

- Ability to transform complex, messy datasets into analytics-ready assets  
- Strong understanding of cloud data platforms and BI workflows  
- End-to-end ownership from ingestion to executive dashboards  
- Scalable design principles applicable across multiple industries  

---

## 🧩 Dimensional Model  

![DimensionalModel](https://github.com/user-attachments/assets/76a07d40-1e9f-4a73-a0d6-7d53d939a6af)

---

## 🔄 Data Pipeline (Azure Data Factory)  

![DataPipeline](https://github.com/user-attachments/assets/46c88787-82a2-4c80-9733-c79720b0c662)

---

## 📊 Power BI Dashboard  

The BI layer includes interactive dashboards with:
- Time-based trend analysis  
- Location and category-level insights  
- Risk and outcome distribution metrics  
- Geographic and segment-based heatmaps  
- Executive summary KPIs and drill-down views  
---

Feel free to fork, explore, or adapt this project.  
📬 Let’s connect on [LinkedIn](https://www.linkedin.com/in/rsputcha/) — open to Data Engineering, Analytics, and BI roles.
