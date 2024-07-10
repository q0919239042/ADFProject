# Covid-19 Azure Data Factoty Pipeline and Power BI Reporting

## Project Introduction:
  The COVID19-ADF project leverages Microsoft Azure services to collect, process, and visualize COVID-19 data from the European Centre for Disease Prevention and Control (ECDC). By integrating population data, the project provides comprehensive insights into the pandemic's impact across Europe in 2020.

## Solution Architecture:
![img](https://github.com/q0919239042/ADFProject/blob/main/image/project_architecture.png)

## Key components and workflow:
* **Data Source:** Data is sourced from the ECDC and additional population datasets.
* **Data Processing:** Azure Data Factory (ADF) orchestrates the Extract, Transform, Load (ETL) pipeline. Transformations are performed using ADF, HDInsight, and Databricks.
* **Data Storage:** Processed data is stored in an Azure SQL Database.
* **Data Visualization:** Power BI is used to create detailed reports and dashboards, facilitating in-depth analysis.
