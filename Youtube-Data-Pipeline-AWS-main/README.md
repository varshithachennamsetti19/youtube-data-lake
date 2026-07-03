This project demonstrates the design and implementation of an end-to-end, cloud-native ETL pipeline on AWS for processing and analyzing YouTube trending video statistics. The pipeline ingests raw CSV and JSON datasets from Kaggle, stores them in Amazon S3, and automates data transformation using AWS Glue and AWS Lambda. The processed data is converted into the Parquet format and organized into a multi-layer data lake architecture consisting of Raw, Cleansed, and Analytics layers.

AWS Glue Crawlers and the Glue Data Catalog automatically discover schemas and maintain metadata, enabling serverless SQL querying through Amazon Athena. Scheduled Glue Workflows orchestrate the ETL process, ensuring that data is continuously transformed and analytics-ready. The final curated dataset is visualized using Amazon QuickSight, providing interactive dashboards that highlight regional trends, video engagement, category performance, and other key YouTube analytics.

This project showcases modern data engineering practices, including scalable cloud storage, automated ETL workflows, metadata management, serverless analytics, and business intelligence reporting using AWS services.

Key Features
Built an end-to-end ETL pipeline using AWS cloud services for YouTube analytics.
Implemented a multi-layer data lake architecture (Raw → Cleansed → Analytics) using Amazon S3.
Automated CSV and JSON data transformation using AWS Glue ETL Jobs and AWS Lambda.
Converted datasets into the Parquet format to improve storage efficiency and query performance.
Configured AWS Glue Crawlers and Data Catalog for automated schema discovery and metadata management.
Queried analytics-ready datasets using Amazon Athena without managing infrastructure.
Orchestrated scheduled ETL workflows using AWS Glue Workflows.
Developed interactive Amazon QuickSight dashboards for visualizing YouTube video trends and engagement metrics.
Monitored pipeline execution using AWS CloudWatch and secured AWS resources through IAM roles and policies.
