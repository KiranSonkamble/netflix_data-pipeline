# Netflix Data Pipeline
#### Purpose: To develop and demonstrate proficiency in Azure Databricks Workflow and Delta Live Tables.
### Overview
This project aims to build a robust data pipeline using Azure Databricks. The pipeline will ingest, process, and store Netflix data, leveraging Databricks' powerful data engineering and streaming capabilities.

## epic_1:
Data Source = "Tableau Sample Netflix Dataset"

Tools & Tech: Azure Services, Azure Data Factory, Azure Databricks(Unity Catalog), Databricks Workflow, Databricks DLT, Git and Github,
Azure AD, RBAC, ADLS gen2, Power BI.

create Azure resources and services and plan the architecture of the project

![image alt](https://github.com/KiranSonkamble/netflix_data-pipeline/blob/main/Project_architecture.png)

## epic_2:
load all the data from github to bronze layer using Azure data factory

![image alt](https://github.com/KiranSonkamble/netflix_data-pipeline/blob/aca790f77c0ba341eef6c792b02d473ea0f8cf67/adf.jpeg)

create increametal_ingestion using azure databticks autoloader

## epic_3:
Using Workflow ingest the data from bronze to silver layer

Pipeline is scheduled for every 1 hr.

![image alt](https://github.com/KiranSonkamble/netflix_data-pipeline/blob/main/workflow-1.png)
![image alt](https://github.com/KiranSonkamble/netflix_data-pipeline/blob/main/SheduledPipeline.png)

## epic_4:
4_silver transform data" where data cleaning and transformation occured. Storing it after transformation to silver layer container.

## epic_5:
5_Lookup notebook2 to shedule the workflow to run on user defined weekday
Run my 'netflix_title' file on weekday "5" using workflow

![image alt](https://github.com/KiranSonkamble/netflix_data-pipeline/blob/main/wf_weekday.png)

## epic_6:
creating a final notebook to load all the data into catalog using delta live table

![image alt](https://github.com/KiranSonkamble/netflix_data-pipeline/blob/main/dlt_intially.png)
![image alt](https://github.com/KiranSonkamble/netflix_data-pipeline/blob/main/catalog_data.png)

## epic_7: 
Sharing the data to Power BI or Azure Synapse Analytics via delta share.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Any suggestions and recommendations are welcomed.
## **THANK YOU**

