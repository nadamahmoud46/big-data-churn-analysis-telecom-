

# 📊 Telecom Customer Churn Analysis on AWS

End-to-end Big Data Pipeline | Real-Time + Batch | Power BI Dashboards

## 🚀 Project Overview

Telecom companies struggle with:

1-High churn rates

2-Scattered, inconsistent data sources

3-Missing or incomplete KPIs needed for strategic decisions

**➡️ The pipeline processed more than 2 million customer and usage records, combining batch datasets with real-time streaming events.**

**This project builds a full big-data analytics pipeline on AWS to unify telecom data, process it at scale, and deliver actionable churn insights.**

## 🏗️ Architecture Overview

<img width="986" height="553" alt="Project architecture" src="https://github.com/user-attachments/assets/cd96052f-c55d-44ba-8c84-e1a7298185cc" />

### Data Ingestion

| Source           | Technology      | Description                                |
| ---------------- | --------------- | ------------------------------------------ |
| Batch Data       | **Apache NiFi** | Customer info, plans, usage history        |
| Streaming Events | **Kafka**       | Real-time events, top-ups, support tickets |


### Data Lake

**Amazon S3** → Centralized storage for raw, processed, and curated data

### ETL, Modeling & Orchestration

**AWS Glue Spark Jobs**

1-Data cleaning

2-Feature engineering

3-Churn modeling

4-RFM scoring

5-KPI computation

<img width="1927" height="1281" alt="Untitled" src="https://github.com/user-attachments/assets/77379ba9-b3e8-44db-8b96-376174f59f32" />

**AWS Glue Workflows** for orchestration and automation

<img width="848" height="255" alt="orchestration" src="https://github.com/user-attachments/assets/a87a3552-f76b-4c0d-a5ca-4cdf9da4f41d" />


### Analytics Layer

**Amazon Athena** → Interactive SQL analytics on S3

**Power BI** → Dashboards, insights, churn trends, and KPI visualizations

### 📦 Dataset

**📌 Total dataset size: over 2,000,000 telecom records**
**📌 Includes both batch and real-time data streams.**


### Dataset domains:

- Customer profiles

- Recharge / top-up transactions

- Usage history (voice, SMS, data)

- Billing & revenue

- Support / escalation tickets

- Real-time events (Kafka streams)

## 📌 Key KPIs
### Revenue Metrics

**-** ARPU by segment: Avg revenue per user per segment

**-** ARPU per customer per month

**-** CLV (Customer Lifetime Value): projected customer revenue

### Churn Metrics

**-** Churn by plan

**-** Churn rate per year

**-** Early warning signals:

**-** low usage

**-** decreased top-ups

**-** frequent support tickets

### Usage & Behavioral Metrics

**-** Usage_per_customer_month

**-** RFM per month (Recency–Frequency–Monetary)

**-** Heavy users

**-** Low usage users

**-** High frequency top-ups

### Support Metrics

**-** Escalation Rate per month

**-** Support-triggered churn indicators

## 📈 Insights & Outcomes

**-** Identified high-risk customer segments before churn

**-** Built automated KPI pipelines with Glue + Athena

**-** Delivered Power BI dashboards for executive decision-making

**-** Improved data consistency by unifying all sources into a single S3-based data lake

## 🔧 Tools & Technologies

**AWS:** S3, Glue, Athena, IAM, CloudWatch

**Stream & Batch:** Kafka, NiFi

**Data Processing:** PySpark, Glue ETL

**Visualization:** Power BI

**Languages:** Python, SQL

## 💡 Recommendations for Telecom Operators

**-** Move curated datasets to Amazon Redshift for low-latency BI

**-** Build a 360° Customer View to improve customer service

**-** Integrate network performance data to enhance churn prediction
