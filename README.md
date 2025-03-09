# adf_adb_project


In today's digital landscape, organizations generate and store massive amounts of data across various platforms, including cloud storage, databases, and file systems. Managing, validating, and efficiently transferring this data is a critical challenge.

This project aims to demonstrate data ingestion, validation, and movement using Azure Data Factory (ADF), Azure Data Lake Storage (ADLS), and Azure Functions. Specifically, we will:

Extract data from a web storage source (GitHub) and load it into Azure Data Lake using Azure Data Factory.
Validate the ingested data using Azure Functions.
Classify the data:
Move valid data to a staging folder for further processing.
Move invalid data to an error folder for investigation.
Load the validated data into a database for structured storage and analysis.
To achieve this, the project will leverage:

Linked Services to establish connections between source and destination.
Datasets to define the structure of data being processed.
Pipelines to orchestrate the data movement and transformation.
This project will showcase end-to-end data integration using Azure services, ensuring efficient, automated, and scalable data workflows.
