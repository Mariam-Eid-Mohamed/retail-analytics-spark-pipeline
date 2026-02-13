# 🛒 Retail Analytics Big Data Pipeline (PySpark + HDFS + Hive)

## 📌 Project Overview

This project demonstrates an on-premise **Big Data analytics pipeline** built using the Hadoop ecosystem.
The goal was to transform raw retail transaction datasets into structured analytical outputs that support revenue analysis, customer insights, and product performance monitoring.

The pipeline processes JSON-based retail data stored in HDFS using PySpark transformations and publishes aggregated analytics into Hive tables for downstream reporting.

---

## 🏗️ Architecture Overview

**Data Flow:**

Raw JSON Files → HDFS Staging Zone → PySpark Transformations → Hive Analytics Tables

Key components include:

- HDFS for distributed storage
- PySpark for scalable data processing
- Hive for analytics-ready tables
- On-prem Hadoop environment

---

## 📂 Data Sources

The pipeline uses three primary datasets:

- Orders
- Sales
- Products

These datasets simulate real-world retail transaction data containing product details, customer purchases, and revenue metrics.

---

## ⚙️ Pipeline Features

### 🔹 Data Ingestion

- Loaded JSON files into HDFS staging zone
- Organized structured directories for distributed processing

### 🔹 Data Transformation (PySpark)

Built analytical transformations including:

- Total revenue per product
- Revenue by sales channel
- Daily sales metrics
- Top customers by spending
- Category-level performance
- Weekly & monthly revenue trends
- Discount impact analysis
- Low-performing product detection

### 🔹 Analytics Layer (Hive)

Selected aggregated datasets were written into Hive tables under:

```
retail_analytics
```

These tables provide a curated layer for BI dashboards and analytical queries.

---

## 📊 Business Value

The pipeline produces actionable insights such as:

- Identification of top revenue-generating products
- Detection of underperforming inventory
- Customer segmentation by spending behavior
- Channel-level sales performance analysis

This enables data-driven decision-making for retail operations and revenue optimization.

---

## 🧰 Tech Stack

- PySpark
- Hadoop HDFS
- Apache Hive
- Python
- On-Prem Big Data Environment

---

## 🚧 Future Improvements

- Add orchestration using Airflow
- Introduce dimensional modeling (Fact & Dimension tables)
- Integrate BI dashboards
- Add data quality validation layer

---

## 👩‍💻 Author

**Mariam Eid Mohamed**
Big Data Engineering Trainee | Data Engineering Enthusiast
