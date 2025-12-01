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
### Data Ingestion

**Apache NiFi** → Batch ingestion (customer info, plans, usage history)

**Apache Kafka** → Streaming ingestion (real-time events, top-ups, support tickets)

### Data Lake

**Amazon S3** → Centralized storage for raw, processed, and curated data

### ETL, Modeling & Orchestration

**AWS Glue Spark Jobs**

1-Data cleaning

2-Feature engineering

3-Churn modeling

4-RFM scoring

5-KPI computation

**AWS Glue Workflows** for orchestration and automation

### Analytics Layer

**Amazon Athena** → Interactive SQL analytics on S3

**Power BI** → Dashboards, insights, churn trends, and KPI visualizations

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
