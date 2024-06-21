<div align="center">
  <h1 style="color:#8a2be2; margin-right: 20px;"># 📊 YouTube Data Analysis Project by Yuva Krishna 🎥✨</h1>
</div>
  
## Overview
This project aims to securely manage, streamline, and perform analysis on structured and semi-structured YouTube videos data based on video categories and trending metrics.

## Project Goals
1. **Data Ingestion**: Build a mechanism to ingest data from different sources. 📥
2. **ETL System**: Transform raw data into the proper format. 🔄
3. **Data Lake**: Centralize data storage from multiple sources. 🌊
4. **Scalability**: Ensure the system scales with increasing data size. 📈
5. **Cloud**: Use AWS to process vast amounts of data. ☁️
6. **Reporting**: Build a dashboard to provide clear visual insights. 📊

<div align="center">
  <img src="https://github.com/YuvaKrishnaThanneru/Youtube-Data-Analysis-Utilizing-ETL/assets/171606388/91a71ba6-a9a5-497a-962d-fbb8357049bb" width="500">
</div>

## Services Utilized
1. **Amazon S3**: Scalable object storage service for data availability, security, and performance. 💾
2. **AWS IAM**: Securely manage access to AWS services and resources. 🔐
3. **Amazon QuickSight**: Scalable, serverless BI service for interactive dashboards. 📊
4. **AWS Glue**: Serverless data integration for ETL operations. 🧩
5. **AWS Lambda**: Run code without managing servers. 🖥️
6. **AWS Athena**: Query data in S3 using standard SQL. 🔍

## Dataset Used
This Kaggle dataset contains statistics (CSV files) on daily popular YouTube videos over several months. Data includes video title, channel title, publication time, tags, views, likes, dislikes, description, comment count, and a category_id field.

[Kaggle YouTube Dataset](https://www.kaggle.com/datasets/datasnaek/youtube-new)

## Key Technologies and Concepts

- **Amazon S3**: Creating a data lake to store large amounts of data with high availability and security.
- **AWS IAM**: Fine-grained access control to AWS resources, ensuring secure management of user permissions.
- **AWS Glue**: Deployed for ETL operations, allowing the transformation and preparation of data for analysis and reporting.
- **AWS Lambda**: Running serverless functions, enabling scalable and efficient data processing without managing server infrastructure.
- **AWS Athena**: Performing SQL queries directly on data stored in S3, facilitating quick and interactive data analysis.
- **Amazon QuickSight**: Utilized to create an interactive and scalable BI dashboard for visualizing key metrics and trends from YouTube data.

## Additional Features and Benefits

- **Data Security**: Ensured through AWS IAM and encryption features in S3, protecting sensitive data during storage and transit. 🔒
- **Automation**: Automated ETL processes using AWS Glue and Lambda, reducing manual intervention and improving efficiency. 🤖
- **Cost Efficiency**: Leveraging serverless services like Lambda and Athena reduces costs by eliminating the need for dedicated server management. 💰
- **Real-time Data Processing**: Enabled through Lambda functions, allowing for near real-time updates and processing of data. ⏱️
- **Extensibility**: The architecture is designed to be easily extendable, allowing the addition of new data sources and processing workflows without major overhauls. 🔄
- **Visualization**: QuickSight dashboards provide interactive and visually appealing representations of data trends and metrics, aiding in quick decision-making. 👁️‍🗨️
- **Scalability**: Built on AWS cloud infrastructure, the solution can seamlessly scale to accommodate growing data volumes and increased analytical demands. 📏
- **Comprehensive Monitoring**: Integrated with AWS CloudWatch for monitoring and logging, ensuring robust observability and quick issue resolution. 📈
