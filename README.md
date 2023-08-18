# Serverless-YouTube-Data-Analytics-Pipeline-on-AWS


## Overview
This project builds an automated big data pipeline for ingesting, processing, and analyzing YouTube video trend data at scale. It provides actionable insights into YouTube viewing patterns and video performance based on categories, channels, titles, and other attributes.

The pipeline follows modern data engineering best practices using a serverless architecture on AWS cloud platform. This enables secure, resilient, and cost-efficient analysis of large YouTube datasets.


## Pipeline Orchestration
The ETL process is orchestrated on AWS as follows:

- Streaming YouTube data lands into S3 data lake
- Glue crawlers infer schema and populate Data Catalog
- Glue ETL jobs transform and process data at scale
- Cleansed data is stored back into S3
- Athena and QuickSight enable analysis and visualization

## Goals

- **Data Ingestion** - Implement mechanisms to ingest streaming YouTube data from multiple sources into cloud storage.

- **Scalable Data Processing** - Build reusable ETL pipelines that can transform raw data into analytical datasets at scale. 

- **Cloud Data Lake** - Create a durable and secure data lake on cloud object storage for analytical workloads.

- **Managed Analytics** - Leverage serverless querying and visualization services to unlock insights.

- **Adaptive Capacity** - Implement auto-scaling infrastructure that can adapt to increasing data volumes.

- **Actionable BI** - Deliver interactive business intelligence dashboards for content creators and marketers.

