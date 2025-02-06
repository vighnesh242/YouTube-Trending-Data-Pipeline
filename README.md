# YouTube-Trending-Data-Pipeline
## Overview
This project focuses on collecting, processing, and analyzing YouTube trending video data to uncover insights based on categories and engagement metrics. The goal is to build a scalable and cloud-based data pipeline that handles structured and semi-structured data efficiently, enabling better trend analysis and reporting.

## Project Goals
Data Ingestion – Set up a pipeline to fetch YouTube trending data from multiple sources.
ETL Process – Transform raw JSON and CSV data into a structured format suitable for analysis.
Data Lake – Store processed data in a centralized repository for easy accessibility.
Scalability – Ensure the system can handle increasing data volume efficiently.
Cloud Integration – Use AWS to process large-scale data without relying on local machines.
Reporting & Insights – Build an interactive dashboard to visualize key trends and patterns.

## AWS Services Used
Amazon S3 – Stores raw and processed data securely with high availability.
AWS IAM – Manages user access and security across AWS services.
AWS QuickSight – Creates dashboards and visual reports for data-driven insights.
AWS Glue – Automates data cleaning and transformation using ETL workflows.
AWS Lambda – Processes and ingests data in a serverless environment.
AWS Athena – Runs SQL queries directly on S3 data for fast and interactive analysis.

## Dataset Used
The dataset used comes from Kaggle’s YouTube Trending Videos. It contains daily statistics on the most popular YouTube videos across multiple regions, including:

Video title, channel name, and publishing time
Engagement metrics such as views, likes, dislikes, and comments
Tags and descriptions for video content
A category mapping file to classify videos into relevant genres
