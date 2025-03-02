# YouTube Analysis

## Data Engineering YouTube Analysis Project by Vamsi Kankanala
## Overview

This project focuses on securely managing, streamlining, and analyzing structured and semi-structured YouTube video data. The analysis is based on video categories and trending metrics, helping derive insights from popular content.

## Project Goals

Data Ingestion – Develop a mechanism to collect data from multiple sources.
ETL System – Transform raw data into a structured format for analysis.
Data Lake – Store data in a centralized repository for efficient access and management.
Scalability – Ensure the system can handle increasing data volumes effectively.
Cloud Integration – Leverage AWS for scalable data processing and storage.
Reporting – Build an interactive dashboard to visualize key insights.

## AWS Services Used

Amazon S3 – Scalable object storage for securely storing raw and processed data.
AWS IAM – Identity and access management for securing AWS resources.
Amazon QuickSight – Cloud-based BI tool for interactive data visualization.
AWS Glue – Serverless data integration service for data discovery, transformation, and preparation.
AWS Lambda – Serverless computing to automate data processing tasks.
AWS Athena – Interactive query service for analyzing S3-stored data without loading it into a database.

## Dataset Used

The dataset, sourced from Kaggle, contains statistics on daily trending YouTube videos across multiple regions. Each region has a separate CSV file with up to 200 trending videos per day. The dataset includes:
Video title, channel name, publication time, and tags
Metrics: Views, likes, dislikes, and comment count
Description and category_id, which varies by region and is mapped in a JSON file
This project aims to uncover trends, patterns, and insights from YouTube's trending videos using AWS-based data engineering solutions.

[Kaggle Dataset](https://www.kaggle.com/datasets/datasnaek/youtube-new).

## Architecture Diagram
![## Architecture Diagram](https://github.com/Vamsikankanala1428/Youtube_Analysis/blob/main/architecture.jpeg)

