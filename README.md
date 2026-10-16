# Singapore EV Charging Data Engineering Project

An end-to-end data engineering ETL project exploring Singapore's electric vehicle (EV) charging infrastructure using Python, Pandas, PostgreSQL and SQL. Completed collaboratively as part of a group project.

# Project Overview

This project explores the distribution of EV charging points across Singapore. The workflow covers batch dynamic data extraction from the LTA DataMall API, data cleaning and transformation, PostgreSQL integration, and SQL-based analysis.

A supplementary postal code reference dataset was cleaned and incorporated separately to support geographical analysis. This reference dataset was not part of the original API response.

# Project Workflow

1. Data Extraction: Retrieved EV charging points batch data from the LTA DataMall API.
2. Data Cleaning and Transformation: Used Python and Pandas to process the extracted data, handle missing or inconsistent values, and prepare it for database integration.
3. Database Integration: Used SQLAlchemy to facilitate the connection between Python and PostgreSQL and load processed data into the database.
4. Used SQL and Jupyter Notebook to explore charging point distribution and operator-level patterns.
5. Visualisation: The team developed a Power BI dashboard to present selected findings.

# My Contributions

My primary contributions focused on data extraction, preparation, database loading, analysis and project presentation.
# 1. API Data Extraction and Processing
- Worked with the LTA DataMall EV Charging Points Batch (EVCBatch) API.
- Retrieved EV charging infrastructure dynamic data for Singapore.
- Processed nested JSON structures containing charging locations, charging points, plug types and EV charging-point identifiers.
- Explored methods for flattening nested JSON into structured tables for downstream processing.
# 2. Data Cleaning and Transformation
- Used Python and Pandas to clean and transform the extracted data.
- Handled missing values, empty strings, inconsistent spacing and data-format issues.
- Reshaped nested data into structured tabular formats.
- Prepared cleaned datasets for database loading and subsequent analysis.
# 3. PostgreSQL Database Integration
- Used SQLAlchemy, including create_engine(), to establish a Python-to-PostgreSQL connection.
- Loaded prepared data into PostgreSQL for structured storage and querying.
- Worked with relational tables to support downstream data analysis.
# 4. Supplementary Postal-Code Dataset
- The project also incorporated a separately sourced postal-code dataset, provided as postal_code_information.csv.This dataset was not part of the original LTA DataMall API response. I have looked into the dataset but it was cleaned and incorporated separately by one of my teammate to supplement the charging infrastructure data and support geographical analysis.
# 5. SQL Analysis Using Jupyter Notebook
- Used SQL and PostgreSQL data to investigate EV charging infrastructure.
- Contributed to operator-level analysis, including charging-point distribution and dominant operators across regions.
- Explored charging characteristics such as connector types, charging power and pricing where the required data was available.
- Documented the data preparation and analysis workflow in Jupyter Notebook.
# 6. Project Presentation
- Contributed to preparing the final team presentation.
- Helped communicate the project workflow, data preparation process, findings and key challenges.

Scope of contribution: My primary focus was the data engineering workflow and notebook-based analysis. I did not develop the Power BI dashboard.

# Technologies Used
- Python
- Pandas
- SQLAlchemy
- PostgreSQL
- SQL
- Jupyter Notebook
- Microsoft Power BI (team project; dashboard developed by a teammate)
- Git and GitHub

# Data Pipeline

The main workflow can be summarised as:
LTA DataMall API → Python → JSON Processing → Pandas Data Cleaning and Transformation → SQLAlchemy → PostgreSQL → SQL Analysis
The supplementary postal-code dataset followed a separate preparation process before being incorporated into the project.

# Key Learning Outcomes

Through this project, I gained practical experience in:
- Extracting data from a REST API.
- Working with nested JSON and transforming it into structured tables.
- Identifying and handling data-quality issues.
- Connecting Python applications to PostgreSQL using SQLAlchemy.
- Loading and querying data in a relational database.
- Using SQL to analyse real-world infrastructure data.
- Collaborating on a data engineering project and communicating technical findings.

# Acknowledgements

This was a 4-member group project that was completed collaboratively as part of Generation Singapore's Junior Data Engineer programme. I acknowledge my teammates' contributions to the overall pipeline, database design, Power BI dashboard and other project components.

This repository documents my individual contributions alongside selected deliverables from the collaborative project.


