# tokyo-olympic-azure-data-engineering-project
Analyze Olympic data using various tools and technologies, including Azure Data Factory, Data Lake Gen 2, Synapse Analytics, and Azure Databricks.

WORKFLOW


![Workflow](https://github.com/Sandeep1203tech/tokyo-olympic-azure-data-engineering-project/assets/78650502/132e604d-7739-47e6-a1da-7b461e344950)


Workflow

-> Extract data from API using Azure data factory(data pipeline tool)- this will create a flow and load our data onto the azure data lake storage.

-> Using the raw data we will write the spark code using azure databricks and transform our data and load our data back to our transform data lake storage.

-> We will use synapse analytics to run the SQL Queries on top of the transform data so that we can find the insights and get the visualization on top of it.

-> olympic data Source- Kaggle

