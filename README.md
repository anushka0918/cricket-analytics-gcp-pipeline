# 🏏 Cricket Analytics Data Engineering Pipeline

A comprehensive end-to-end data engineering solution built on Google Cloud Platform for real-time cricket statistics analysis and business intelligence visualization.

## 🚀 Project Overview

This project demonstrates modern data engineering practices by building a scalable, serverless pipeline that ingests cricket statistics from external APIs, processes the data through Google Cloud services, and delivers actionable insights via interactive dashboards. The solution showcases cloud-native architecture, real-time processing, and enterprise-grade analytics capabilities.

## 🏗️ Architecture Diagram

Cricbuzz API → Python ETL → Cloud Storage → Cloud Functions → Dataflow → BigQuery → Looker Studio


## 💡 Key Features

- **🔄 Real-time Data Ingestion**: Automated cricket statistics retrieval from Cricbuzz API
- **☁️ Serverless Architecture**: Cost-effective, auto-scaling cloud infrastructure
- **🔧 Event-Driven Processing**: Automated pipeline triggers on data upload
- **📊 Enterprise Analytics**: Scalable data warehouse with BigQuery
- **📈 Interactive Dashboards**: Business intelligence visualization with Looker Studio
- **🛡️ Production-Ready**: Error handling, monitoring, and logging capabilities

## 🛠️ Technology Stack

### **Cloud Platform**
- **Google Cloud Platform (GCP)** - Primary cloud infrastructure
- **Google Cloud Storage** - Data lake for raw file storage
- **Cloud Functions** - Serverless compute for pipeline orchestration
- **Dataflow** - Apache Beam-based stream/batch processing
- **BigQuery** - Enterprise data warehouse and analytics engine
- **Looker Studio** - Business intelligence and visualization platform

### **Programming & Tools**
- **Python 95.9%** - Primary development language
- **JavaScript 4.1%** - User-defined functions and frontend logic
- **Apache Beam** - Unified programming model for data processing
- **REST APIs** - External data source integration


## 🔧 Pipeline Architecture

### **1. Data Extraction Layer**
- **API Integration**: Connects to Cricbuzz API for live cricket statistics
- **Data Validation**: Ensures data quality and consistency
- **Error Handling**: Robust exception management for API failures

### **2. Storage Layer**
- **Cloud Storage**: Scalable data lake for raw CSV files
- **Partitioning**: Organized data structure for efficient querying
- **Versioning**: Historical data preservation and audit trail

### **3. Processing Layer**
- **Cloud Functions**: Event-driven triggers for automated processing
- **Dataflow Jobs**: Scalable ETL operations using Apache Beam
- **Data Transformation**: Cleaning, enrichment, and normalization

### **4. Analytics Layer**
- **BigQuery**: Enterprise data warehouse for complex analytics
- **SQL Analytics**: Advanced querying capabilities for business insights
- **Performance Optimization**: Clustered tables and partitioning strategies

### **5. Visualization Layer**
- **Looker Studio**: Interactive dashboards and reports
- **Real-time Updates**: Live data refresh for current match statistics
- **Business Metrics**: KPIs and performance indicators for stakeholders

## 🚀 Getting Started

### **Prerequisites**
- Google Cloud Platform account with billing enabled
- Python 3.8+ installed locally
- Git for version control
- Basic knowledge of GCP services

### **GCP Services Setup**
1. **Enable Required APIs**:
gcloud services enable storage.googleapis.com
gcloud services enable cloudfunctions.googleapis.com
gcloud services enable dataflow.googleapis.com
gcloud services enable bigquery.googleapis.com
