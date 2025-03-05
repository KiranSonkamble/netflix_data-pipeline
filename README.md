# netflix_data-pipeline
Data Source = "Tableau Sample Netflix Dataset"

Tools & Tech: Azure Services, Azure Data Factory, Azure Databricks(Unity Catalog), Databricks Workflow, Databricks DLT, Git and Github,
Azure AD, RBAC, ADLS gen2, Power BI

## epic_1:
create Azure resources and services and plan the architecture of the project

## epic_2:
load all the data from github to bronze layer using Azure data factory
create increametal_ingestion using azure databticks autoloader

## epic_3:
Using Workflow ingest the data from bronze to silver layer

## epic_4:
4_silver transform data" where data cleaning and transformation occured. Storing it after transformation to silver layer container.

## epic_5:
5_Lookup notebook2 to shedule the workflow to run on user defined weekday
Run my 'netflix_title' file on weekday "5" using workflow

## epic_6:
creating a final notebook to load all the data into catalog using delta live table

## epic_7: 
Sharing the data to POwer BI or delta share to azure Synapse Analytics


