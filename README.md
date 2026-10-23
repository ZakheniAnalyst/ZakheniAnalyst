## Hi there, I'm Zakheni 👋

**Data Engineer | Analytics & BI**

I build reliable data pipelines and turn raw data into insights businesses can act on. My work covers ingestion, transformation, data quality, dimensional modelling and dashboards, on both Databricks and the modern data stack.

### 🛠️ Core Skills
- **Data Engineering:** Python, SQL, PySpark, Databricks, Snowflake, dbt
- **Cloud & Platforms:** Azure, AWS, Unity Catalog, Delta Lake
- **Analytics & BI:** Star schema modelling, Power BI, DAX, AI/BI dashboards

### 🚀 Featured Engineering Projects

#### 💳 Finance Fraud & Loans: Lakeflow Declarative Pipeline
*Medallion pipeline with data quality quarantine and fraud risk scoring*
- **Architecture:** Auto Loader ingests 11 CSV files into Bronze streaming tables, cleaned in Silver, modelled as a star schema in Gold, then surfaced in an AI/BI dashboard. Records that fail hard data quality rules are routed to a Quarantine table with failure reasons.
- **Stack:** Databricks Free Edition, Lakeflow Declarative Pipelines, Auto Loader, Unity Catalog, Serverless Compute, PySpark, SQL
- **Highlights:** Processed about 50k transactions with roughly 7% injected errors. Handled mixed date formats, country typos and duplicates, applied data quality expectations, and built risk rules with an anomaly score plus daily activity, branch risk and loan portfolio aggregates.
- 🔗 Repo: https://github.com/ZakheniAnalyst/Spark-Declarative-Pipeline-Finance-Fraud-Loans-

#### 🛒 E-Commerce ELT Pipeline: AWS S3 → Snowflake → dbt → Power BI
*Cloud-native ELT with tested, dimensional models*
- **Architecture:** Parquet files land in AWS S3, load into a Snowflake RAW schema, and are transformed with dbt through Staging, Intermediate and Marts layers, then consumed in Power BI.
- **Stack:** AWS S3, Snowflake, dbt, Power BI, Python, GitHub
- **Highlights:** Row count validation and referential integrity checks on load, dbt data quality tests, and a star schema (`dim_customers`, `dim_products`, `fct_orders`, `fct_order_items`) built from 5 related tables.
- 🔗 Repo: https://github.com/ZakheniAnalyst/ecommerce-s3-snowflake-dbt-pipeline

#### 📊 E-Commerce Data Engineering & Analytics Pipeline (Databricks)
*End-to-end Lakehouse pipeline with governed data and BI reporting*
- **Architecture:** CSV files in a Unity Catalog Volume flow through Bronze, Silver and Gold Delta Lake layers using Spark Declarative Pipelines and Auto Loader, feeding a 5-page Power BI report.
- **Stack:** Databricks, PySpark, SQL, Delta Lake, Unity Catalog, Power BI
- **Highlights:** Schema inference with rescued data handling, deduplication and key-based joins in Silver, and a Gold star schema with daily and monthly sales aggregates. Dashboard pages cover Executive Overview, Sales & Profitability, Customer & Regional Analysis, Marketing, Delivery & Returns, and Product Performance.
- 🔗 Repo: https://github.com/ZakheniAnalyst/ecommerce-spark-declarative-pipeline

#### 🏥 Azure Databricks Healthcare End-to-End Pipeline
*Healthcare data pipeline on Azure Databricks*
- **Repo:** [Azure-Databricks-HealthCare-End-to-End-Pipeline](https://github.com/ZakheniAnalyst/Azure-Databricks-HealthCare-End-to-End-Pipeline)
- **Stack:** Azure, Databricks, PySpark, SQL

### 📚 AnalystLab Africa
Weekly data analytics assignments and projects (Weeks 1 to 5) covering the core analytics workflow.

### 📫 Connect
- LinkedIn: https://www.linkedin.com/in/zakheni-mathonsi-466758335/
