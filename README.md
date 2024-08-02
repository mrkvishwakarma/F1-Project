
# Azure Databricks for Formula1 Data Engineering Project

## Welcome!
I am looking forward to helping you learn one of the in-demand data engineering tools in the cloud, Azure Databricks! This course focuses on implementing a data engineering solution using Azure Databricks and Spark core for a real-world project of analyzing and reporting on Formula1 motor racing data.

This course is unique among Udemy offerings for Azure Databricks. Once you have completed the course and all the assignments, I strongly believe you will be ready to start a real-world data engineering project on your own and become proficient in Azure Databricks. Additionally, the course includes lessons on Azure Data Lake Storage Gen2, Azure Data Factory, and PowerBI. The primary focus is on Azure Databricks and Spark core, but it also covers relevant concepts and connectivity to the other mentioned technologies. Please note that the course doesn't cover Spark streaming or Spark ML and has been taught using PySpark and Spark SQL; it doesn't cover Scala or Java.

The course follows a logical progression of a real-world project implementation with technical concepts explained as the Databricks notebooks are built simultaneously. Even though this course is not specifically designed to teach the skills required for passing the Azure Data Engineer Associate Certification Exam DP203, it can greatly help you acquire most of the necessary skills for the exam. Similarly, the course teaches the skills required to pass the Databricks Certified Data Engineer Associate Certification.

I value your time as much as I do mine, so I have designed this course to be fast-paced and to the point. Also, the course has been taught in simple English with no jargon. I start from the basics, and by the end of the course, you will be proficient in the technologies used.

## Project Goals
### Azure Databricks
- Building a solution architecture for a data engineering solution using Azure Databricks, Azure Data Lake Gen2, Azure Data Factory, and Power BI.
- Creating and using Azure Databricks service and understanding the architecture of Databricks within Azure.
- Working with Databricks notebooks and using Databricks utilities, magic commands, etc.
- Passing parameters between notebooks and creating notebook workflows.
- Creating, configuring, and monitoring Databricks clusters, cluster pools, and jobs.
- Mounting Azure Storage in Databricks using secrets stored in Azure Key Vault.
- Working with Databricks Tables and Databricks File System (DBFS).
- Using Delta Lake to implement a solution using Lakehouse architecture.
- Creating dashboards to visualize outputs.
- Connecting to Azure Databricks tables from PowerBI.

### Spark (Only PySpark and SQL)
- Spark architecture, Data Sources API, and Dataframe API.
- PySpark: Ingesting CSV, simple, and complex JSON files into the data lake as parquet files/tables.
- PySpark: Transformations such as Filter, Join, Simple Aggregations, GroupBy, Window functions, etc.
- PySpark: Creating local and temporary views.
- Spark SQL: Creating databases, tables, and views.
- Spark SQL: Transformations such as Filter, Join, Simple Aggregations, GroupBy, Window functions, etc.
- Spark SQL: Creating local and temporary views.
- Implementing full refresh and incremental load patterns using partitions.

### Delta Lake
- Emergence of Data Lakehouse architecture and the role of Delta Lake.
- Reading, Writing, Updating, Deleting, and Merging to Delta Lake using both PySpark and SQL.
- History, Time Travel, and Vacuum.
- Converting Parquet files to Delta files.
- Implementing incremental load patterns using Delta Lake.

### Unity Catalog
- Overview of Data Governance and Unity Catalog.
- Creating Unity Catalog Metastore and enabling a Databricks workspace with Unity Catalog.
- Overview of 3-level namespace and creating Unity Catalog objects.
- Configuring and accessing external data lakes via Unity Catalog.
- Development of a mini-project using Unity Catalog to see key data governance capabilities offered by Unity Catalog such as Data Discovery, Data Audit, Data Lineage, and Data Access Control.

### Azure Data Factory
- Creating pipelines to execute Databricks notebooks.
- Designing robust pipelines to deal with unexpected scenarios such as missing files.
- Creating dependencies between activities and pipelines.
- Scheduling the pipelines using Data Factory triggers to execute at regular intervals.
- Monitoring the triggers/pipelines to check for errors/outputs.

## Who This Project Is For
- University students looking for a career in Data Engineering.
- IT developers working in other disciplines who want to move to Data Engineering.
- Data Engineers/Data Warehouse Developers currently working on on-premises technologies or other cloud platforms like AWS or GCP who want to learn Azure Data Technologies.
- Data Architects looking to gain an understanding of the Azure Data Engineering stack.

## Learning Outcomes
By the end of this project, you will:
- Understand how to use Azure Databricks for end-to-end data engineering tasks.
- Gain hands-on experience with data ingestion, transformation, and visualization.
- Learn how to automate and schedule data workflows using ADF.
- Implement security best practices using Azure Key Vault.
- Monitor and manage data pipelines effectively.

## Visuals

### F1-Entity Relationship Diagram
![Entity Relationship Diagram](./images/f1_db_erd.png)

### Ingestion Pipelines
![Ingestion File Pipeline](./images/ingestion_files_pipeline.png)

### Transformation Pipeline
![Transformation Pipeline](./images/trans_pipeline.png)

### Pipelines Logic
![Pipelines Logic](./images/Pipeline_logic.png)
