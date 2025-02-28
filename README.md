# AWS-Based-Stock-Market-Data-Streaming-Analytics-with-Kafka
AWS-Based Stock Market Data Streaming &amp; Analytics with Kafka is a scalable pipeline that simulates real-world stock markets. It uses Apache Kafka for streaming, Amazon S3 for storage, AWS Glue for data transformation, and Amazon Athena for querying. This integration enables real-time stock data processing, trend analysis, and actionable insights.

## 📜 Table of Contents  
- [Business Understanding](#business-understanding)  
- [Data Understanding](#data-understanding)  
- [Technologies](#technologies)  
- [Setup](#setup)  
- [Approach](#approach)  
- [Status](#status)  

## 📈 Business Understanding  
This project aims to simulate real-world stock market conditions by generating, processing, storing, and analyzing real-time stock data. The goal is to provide insights into stock market trends through a highly scalable data pipeline using AWS and Kafka.  

## 🔍 Data Understanding  
The project involves streaming real-time stock data, storing it in Amazon S3, processing it with AWS Glue, and analyzing it using Amazon Athena. The data consists of stock price movements, timestamps, and related metadata.  

## ⚙️ Technologies  
- **Programming Language:** Python  
- **Storage:** Amazon S3  
- **Streaming Tool:** Apache Kafka  
- **Server:** EC2 Instance  
- **Database:** Amazon Athena (SQL)  
- **Automation:** AWS Glue Crawler  

## 🚀 Setup  
1. **Create an EC2 Instance**  
   - Launch an instance with Amazon Linux 2.  
   - Set up a security group and configure inbound rules.  

2. **Install Kafka on EC2**  
   - Install Java and download Kafka.  
   - Start Zookeeper and Kafka server.  

3. **Set Up Kafka Topics and Producers**  
   - Create a topic (`SM`).  
   - Start a producer and consumer.  

4. **Integrate with AWS S3**  
   - Set up an S3 bucket to store streamed data.  

5. **Run AWS Glue Crawler**  
   - Configure a crawler to catalog data in Glue.  

6. **Analyze Data using Amazon Athena**  
   - Run SQL queries to extract insights.  

## 🔬 Approach  
1. Deploy an EC2 instance and configure it for Kafka.  
2. Stream real-time stock data using Kafka producers.  
3. Store the processed data in Amazon S3.  
4. Use AWS Glue to catalog and transform the data.  
5. Query the data with Amazon Athena.  

## 📌 Status  
- [x] Kafka setup on EC2  
- [x] Stock data ingestion  
- [x] S3 integration  
- [x] AWS Glue Crawler setup  
- [x] Amazon Athena query execution  
