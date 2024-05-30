# YouTube Data Analysis ETL Pipeline

![Project Architecture](Data_Architecture_Diagram.png)

## Project Overview

This project is focused on creating ETL (Extract, Transform, Load) pipelines for analyzing YouTube datasets. The goal is to efficiently process and transform YouTube data for analysis and reporting. The project leverages a combination of AWS services and scripting languages to automate and streamline the ETL process.

## Tech Stack

- **AWS S3**: Used for storing the raw YouTube dataset.
- **AWS Lambda**: Triggers the ETL process upon data upload.
- **AWS Glue**: Handles data transformation tasks.
- **AWS Athena**: Facilitates SQL querying and table creation.
- **AWS IAM**: Manages access control and permissions.
- **Python & Shell Scripting**: Used for various scripting tasks within the pipeline.

## Architecture

1. **Data Ingestion**: The YouTube dataset is uploaded to an S3 bucket.
2. **Trigger**: An S3 event triggers an AWS Lambda function.
3. **Transformation**: AWS Lambda invokes AWS Glue to transform the data.
4. **SQL Exposure**: Transformed data is queried using AWS Athena, which also handles table creation.
5. **Access Control**: AWS IAM ensures secure access to all resources involved in the ETL process.


