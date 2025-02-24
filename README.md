# AWS Walmart Sales Analysis

[![Python](https://img.shields.io/badge/Python-3.9+-blue?logo=python)](https://www.python.org/)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-15+-blue?logo=postgresql)](https://www.postgresql.org/)
[![AWS RDS](https://img.shields.io/badge/AWS_RDS-Cloud-blue?logo=amazonaws)](https://aws.amazon.com/rds/)
[![PowerBI](https://img.shields.io/badge/PowerBI-Visualization-yellow)](https://powerbi.microsoft.com/)

A comprehensive sales analysis system leveraging cloud infrastructure and business intelligence tools to derive actionable insights from Walmart sales data.

## 📌 Overview

End-to-end data solution featuring:
- Cloud-based data storage with AWS RDS (PostgreSQL)
- Robust ETL pipelines using Python
- Advanced analytics and forecasting models
- Interactive Power BI dashboards
- Scalable cloud architecture

Key Achievements:
✅ Built scalable data infrastructure on AWS Cloud  
✅ Automated data ingestion and transformation processes   
✅ Created interactive dashboards with 15+ key performance metrics  
✅ Optimized PostgreSQL queries for 40% faster data retrieval

## 🛠️ System Architecture
```mermaid
graph LR
    A[Raw Sales Data] --> B[Python ETL Processing]
    B --> C[AWS RDS PostgreSQL]
    C --> D[Analytical Datamart]
    D --> E[Power BI Visualization]
    E --> F[Report Generation]

