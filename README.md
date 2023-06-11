
# Data Engineering YouTube Analysis Project

## Overview

This project aims to securely manage, streamline, and perform analysis on structured and semi-structured YouTube video data based on video categories and trending metrics. With a passion for data engineering and leveraging my expertise in AWS services, I have designed an architecture and implemented a comprehensive solution for efficient data processing and analysis.
## Project Goals

Throughout the development of this project, I had several goals in mind:

Data Ingestion: I aimed to build a robust mechanism capable of ingesting data from diverse sources. By leveraging the Kaggle dataset containing daily popular YouTube videos, I ensured a reliable and up-to-date data source for analysis.

ETL System: Transforming raw data into a proper format is crucial for meaningful analysis. I dedicated significant effort to develop an ETL (Extract, Transform, Load) system that cleansed the data, performed necessary transformations, and ensured high data quality.

Data Lake: Recognizing the need for centralized data storage, I implemented a data lake using Amazon S3. This decision allowed for secure and scalable storage of YouTube data from multiple sources, ensuring accessibility and flexibility in handling large volumes of data.

Scalability: As the size of the YouTube data grows over time, it is imperative to have a scalable system in place. To address this, I utilized serverless services like AWS Glue, AWS Lambda, and AWS Athena, which enabled seamless scalability without the need for manual infrastructure management.

Cloud Computing: Leveraging the power of the cloud was a vital aspect of this project. By utilizing various AWS services, including S3, IAM, QuickSight, Glue, Lambda, and Athena, I ensured efficient processing of vast amounts of YouTube data, providing cost-effective solutions and reducing the complexity of managing infrastructure.

Reporting: To gain valuable insights from the YouTube data, I created an interactive dashboard using Amazon QuickSight. This allowed me to visualize key metrics, trends, and patterns, enabling easy decision-making and analysis.
## Services Used

Throughout the project, I leveraged the following AWS services:

Amazon S3: By utilizing Amazon S3, I ensured a reliable and scalable data storage solution for the YouTube dataset. Its features, such as scalability, data availability, security, and performance, contributed to the overall success of the project.

AWS IAM: Identity and Access Management played a critical role in securing access to AWS services and resources. I diligently managed access permissions to ensure the project's security and data privacy.

Amazon QuickSight: Utilizing Amazon QuickSight, I created interactive and visually appealing dashboards that provided comprehensive insights into the YouTube data. QuickSight's scalability and machine learning-powered BI capabilities greatly enhanced the project's reporting and analysis capabilities.

AWS Glue: As a serverless data integration service, AWS Glue simplified the process of discovering, preparing, and combining data for analysis. By automating data transformations and providing a unified view of the data, Glue proved to be an invaluable tool in the project.

AWS Lambda: AWS Lambda allowed me to execute code without the need for provisioning or managing servers. I utilized Lambda functions for various data processing tasks, enhancing the project's scalability and efficiency.

AWS Athena: With AWS Athena, I could analyze data directly from Amazon S3 without the need for data loading or database management. Its interactive query service significantly expedited the analysis process.
## Dataset

The dataset used for this project was sourced from Kaggle. It contains statistics on daily popular YouTube videos, including information such as video title, channel title, publication time, tags, views, likes, dislikes, description, comment count, and category ID. By utilizing this dataset, I ensured a comprehensive analysis of YouTube trends and metrics.

You can access the dataset at the following link: https://www.kaggle.com/datasets/datasnaek/youtube-new
## Architecture Diagram

To provide a visual representation of the project's components and data flow, I have created an architecture diagram. It illustrates the seamless integration of AWS services and the efficient processing of YouTube data.

