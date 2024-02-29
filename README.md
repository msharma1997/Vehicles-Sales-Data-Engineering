# Vehicles-Sales-Data-Engineering
Project Overview:
The project involves building a comprehensive data processing pipeline in Azure to handle large-scale data ingestion, transformation, and analytics tasks.

Components Used:
Azure Blob Storage: Used as the initial storage solution for uploading raw data.
Azure Data Factory (ADF):
Task: Ingests data from Blob Storage and loads it into Azure Data Lake Storage (ADLS).
Azure Data Lake Storage (ADLS):
Task: Acts as a centralized storage repository for raw and transformed data.
Azure Databricks:
Task: Performs data transformation using Apache Spark-based analytics.
Azure Synapse Analytics:
Task: Executes SQL queries for data analytics and reporting.
Database Creation: Created a database within ADLS for data querying and analysis.

###############Workflow##########:
Data Ingestion:

Raw data is uploaded to Azure Blob Storage.
![Storage Account raw   transformed data](https://github.com/msharma1997/Vehicles-Sales-Data-Engineering/assets/160339633/75554f8c-a22e-41a6-81e2-7920b7b01fb9)

Azure Data Factory extracts data from Blob Storage and loads it into ADLS.
![ADF Pipeline](https://github.com/msharma1997/Vehicles-Sales-Data-Engineering/assets/160339633/3388ec3d-5d75-4aa6-8b0b-33056f3d5c7e)

Data Transformation:
Azure Databricks processes the ingested data, performing necessary transformations (e.g., cleaning, aggregation).
Databricks Repo Link - https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/5968350211537221/301361542543334/5486328784502366/latest.html

Data Storage:
Transformed data is stored back into Azure Data Lake Storage for future access and analysis.

Data Analytics:
Azure Synapse Analytics is utilized for running SQL queries on the data stored in ADLS, enabling data analysis and reporting.
![Azure synapse analytics sql query](https://github.com/msharma1997/Vehicles-Sales-Data-Engineering/assets/160339633/835b2a5d-4305-4763-92e0-6cdc76e71c65)
![Azure synapse analytics sql query_2](https://github.com/msharma1997/Vehicles-Sales-Data-Engineering/assets/160339633/b5ba5a11-26e1-4dfd-9020-21c3179d401d)


Benefits:

Scalability: Leveraging cloud services allows for scaling resources according to the data volume and processing requirements.
Integration: Seamless integration between Azure services facilitates an end-to-end data pipeline.
Centralization: Data is centralized in Azure Data Lake Storage, simplifying management and access.
Analytics: Azure Synapse Analytics provides robust SQL-based analytics capabilities for deriving insights from the processed data.
Future Considerations:
Automation: Implementing automated scheduling for data pipeline tasks to streamline operations.
Monitoring: Setting up monitoring and alerting mechanisms to track pipeline performance and data quality.
Optimization: Continuously optimizing the pipeline for improved efficiency and cost-effectiveness.
Conclusion:

By leveraging Azure services such as Blob Storage, Data Factory, Databricks, and Synapse Analytics, the project demonstrates a robust solution for managing and analyzing large-scale data in a cloud environment, paving the way for enhanced decision-making and insights generation.
