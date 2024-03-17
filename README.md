# DE-snowpark-python

Data Engineering Pipelines with Snowpark Python
The pipeline will process data incrementally, be orchestrated with Snowflake tasks, and be deployed via a CI/CD pipeline, procedure described - 
1. Load Parquet data to Snowflake using schema inference
2. Setup access to Snowflake Marketplace data
3. Create a Python UDF to convert temperature
4. Create a data engineering pipeline with Python stored procedures to incrementally process data
5. Orchestrate the pipelines with tasks
6. Monitor the pipelines with Snowsight
7. Deploy the Snowpark Python stored procedures via a CI/CD pipeline

requirements - snowflake-snowpark-python[pandas]
snowflake-cli-labs
