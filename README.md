# 📊 AWS Data Confluence

## 🚀 Project Overview

AWS Data Confluence is a real-time, fully serverless data streaming and analytics platform built using Amazon Web Services. It captures live JSON events from a React web application, processes them using AWS Lambda, stores them in Amazon S3 as a scalable data lake, and enables instant SQL-based analytics using AWS Glue and Amazon Athena.

Additionally, Amazon SNS is integrated to send real-time notifications and alerts based on incoming data events, making the system suitable for monitoring and operational use cases.

---

## ✨ Key Features

- 🚀 Real-time data ingestion  
- ☁️ Fully serverless cloud architecture  
- 📦 Scalable data lake using Amazon S3  
- 🔍 Automatic schema discovery with AWS Glue  
- 📊 Instant SQL analytics using Amazon Athena  
- 🔔 Real-time alerts using Amazon SNS  
- 🔐 Secure access using AWS IAM roles  
- 📈 CloudWatch logging and monitoring   
- 📥 The data entered by users appears directly in downloadable CSV log files
---

## 🏗️ System Architecture

```
React Frontend
     ↓
API Gateway (HTTP API)
     ↓
AWS Lambda (Event Processor)
     ↓
Amazon S3 (Data Lake)
     ↓
AWS Glue Crawler → Glue Data Catalog
     ↓
Amazon Athena (SQL Analytics)
     ↓
Amazon SNS (Email / Notification Alerts)
```

---
## 📖 Usage Guide

1. Open the React web app  
2. Enter event data (user action, logs, sales info, etc.)  
3. Click submit to send JSON data in real time  
4. Lambda stores the data in S3  
5. SNS sends alerts 
6. Glue updates schema automatically  
7. Athena queries provide instant insights

---

## ☁️ AWS Services Used

| AWS Service | Purpose |
|------------|---------|
| Amazon API Gateway | Real-time event ingestion |
| AWS Lambda | Processing and storing events |
| Amazon S3 | Data lake storage |
| AWS Glue | Schema detection & catalog |
| Amazon Athena | SQL analytics |
| Amazon SNS | Real-time alerts & notifications |
| AWS IAM | Security roles |
| AWS CloudWatch | Logs & monitoring |

---

## 🔮 Future Enhancements

- 📊 BI dashboards with QuickSight
- 🤖 Machine learning analytics
- ⚡ High-speed streaming with Kinesis
- 📱 Mobile ingestion support
- 🔔 Intelligent alert automation
- 🔐 Advanced security layers

---

Made with ❤️ on AWS.

---
