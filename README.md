# 🚕 Spark Streaming Uber — Real-Time Data Pipeline (Kafka + Spark)

A real-time data streaming project that simulates **Uber ride events**, processes them using **Apache Spark Structured Streaming**, and outputs live analytics such as average fare, trip counts, and route insights.

---

## 🧩 Overview

This project demonstrates how to build an **end-to-end real-time streaming pipeline** using:
- **Kafka** for data ingestion and buffering  
- **Spark Structured Streaming** for real-time data transformation and aggregation  
- **Python** for producing mock ride data  
- **Console / Parquet / Database sinks** for storing and visualizing results  

---

## 🏗️ Architecture

```text
Kafka Producer  --->  Kafka Topic (uber-rides)
                           ↓
                 Spark Structured Streaming
                           ↓
                 Transformed / Aggregated Data
                           ↓
                 Console / Parquet / Dashboard
