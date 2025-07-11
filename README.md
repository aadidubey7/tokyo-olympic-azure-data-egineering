# tokyo-olympic-azure-etl-data-egineering

This is a simple ETL project I developed on the Azure platform to demonstrate how an automated ETL pipeline can be configured and executed using Azure services. The dataset used is available in my GitHub repository, where you can view and download it. The pipeline fetches CSV data from GitHub and stores it in an Azure Storage Account as raw data. It then triggers a Databricks notebook to perform basic transformations, and the processed data is subsequently saved back to ADLS Gen2 storage.
