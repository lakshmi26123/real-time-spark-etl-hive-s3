# Real-Time Spark ETL Pipeline – Hive & S3

## Overview
This project simulates a **scalable, production-grade data engineering solution** for a fast-growing e-commerce company handling millions of daily transactions and user events.  

It implements **batch and real-time streaming pipelines** using **Apache Spark, Hive, Kafka, Airflow, and AWS S3**, demonstrating end-to-end **data ingestion, transformation, storage, and orchestration**.

## Skills / Tools
MySQL · Apache Kafka · Apache Sqoop · AWS Athena · Apache Airflow · Apache Spark · Hive · S3

## CAR Summary
- **Challenge:** Handle millions of daily events with low-latency and high reliability.  
- **Action:** Built batch & streaming Spark ETL pipelines, integrated Kafka for ingestion, Hive & S3 for storage, orchestrated via Airflow, and added automated data validation.  
- **Result:** Simulated **production-ready, fault-tolerant pipelines**, scalable for large workloads and real-time analytics.

## Project Structure
real-time-spark-etl-hive-s3/
├── batch_pipeline/ # Batch ETL code
│ └── batch_etl.py
├── streaming_pipeline/ # Streaming ETL code
│ └── streaming_etl.py
├── airflow_dags/ # Airflow DAGs
│ └── etl_dag.py
├── data/ # Sample input data
├── utils/ # Helper scripts (data validation)
└── docs/ # Diagrams/screenshots
