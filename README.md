# Real-Time Stock Market Data Engineering Project

## Introduction
This project demonstrates an End-to-End Data Engineering solution for processing real-time stock market data using Apache Kafka. The workflow leverages a variety of cutting-edge tools and technologies, including Python and Amazon Web Services (AWS), to process, analyze, and store real-time data efficiently.

## Key Features
- Real-time data ingestion and processing using Apache Kafka.
- Seamless integration with AWS services for data storage and analysis.
- Automated data cataloging and query capabilities.
- Scalable and efficient architecture suitable for large-scale data pipelines.

## Project Objectives
- To process and analyze real-time stock market data.
- To implement a robust and scalable data pipeline.
- To enable efficient data querying and visualization.

## Architecture
The architecture of this project is designed to ensure reliability and scalability. Below is the high-level overview:

![Architecture Diagram](Architecture.jpg)

### Components:
1. **Data Producer**: Streams real-time stock market data.
2. **Apache Kafka**: Serves as the messaging queue for real-time data ingestion.
3. **AWS S3**: Provides reliable storage for processed data.
4. **AWS Glue Crawler & Catalog**: Automates data schema discovery and management.
5. **AWS Athena**: Enables serverless SQL querying of stored data.
6. **AWS EC2**: Hosts Kafka and other necessary services.

## Technologies Used
### Programming Language:
- **Python**: Used for data processing and integration with Kafka and AWS services.

### Amazon Web Services (AWS):
1. **S3 (Simple Storage Service)**: Durable storage for raw and processed data.
2. **Athena**: Serverless querying for data analysis.
3. **Glue Crawler**: Automates schema discovery and table creation in the Glue Catalog.
4. **Glue Catalog**: Centralized metadata management for data in S3.
5. **EC2 (Elastic Compute Cloud)**: Virtual machines to host and manage Apache Kafka.

### Messaging System:
- **Apache Kafka**: For real-time data streaming and ingestion.

## Getting Started
To get started with the project, follow these steps:
1. **Set up the environment:** Install required dependencies and configure AWS credentials.
2. **Deploy Kafka:** Use AWS EC2 to host and configure Apache Kafka.
3. **Ingest Data:** Use Python scripts to produce real-time stock market data to Kafka topics.
4. **Store Data:** Stream the processed data to AWS S3 buckets.
5. **Automate Metadata Management:** Configure AWS Glue Crawlers to catalog data.
6. **Analyze Data:** Query the cataloged data using AWS Athena.

## Prerequisites
- Basic knowledge of Python programming.
- AWS account with appropriate permissions.
- Understanding of Apache Kafka and AWS services.

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/your-repository/real-time-stock-market-data.git
   ```

## Dataset Used
You can use any dataset, we are mainly interested in operation side of Data Engineering (building data pipeline) 

Here is the dataset used in the project - https://github.com/NihalThomas/Real-Time-Stock-Market-Kafka/blob/main/indexProcessed.csv
