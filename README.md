# tokyo-olympic-azure-data-engineering-project
Analyze Olympic data using various tools and technologies, including Azure Data Factory, Data Lake Gen 2, Synapse Analytics, and Azure Databricks.

WORKFLOW


![Workflow](https://github.com/Sandeep1203tech/tokyo-olympic-azure-data-engineering-project/assets/78650502/132e604d-7739-47e6-a1da-7b461e344950)


Workflow

-> Extract data from API using Azure data factory(data pipeline tool)- this will create a flow and load our data onto the azure data lake storage.

![Pipeline](https://github.com/Sandeep1203tech/tokyo-olympic-azure-data-engineering-project/assets/78650502/afa876ed-9f01-4946-a0d9-13b0bb1080c8)


-> Using the raw data we will write the spark code using azure databricks and transform our data and load our data back to our transform data lake storage.

-> We will use synapse analytics to run the SQL Queries on top of the transform data so that we can find the insights and get the visualization on top of it.

![Synapse](https://github.com/Sandeep1203tech/tokyo-olympic-azure-data-engineering-project/assets/78650502/9231b623-2e16-4b2a-b5fa-d7292671bfff)



OLYMPICS 2021 DASHBOARD (Power BI)

![Olym](https://github.com/Sandeep1203tech/tokyo-olympic-azure-data-engineering-project/assets/78650502/51e4738b-4eca-476b-987c-4f55e95a2844)



-> olympic data Source- Kaggle



