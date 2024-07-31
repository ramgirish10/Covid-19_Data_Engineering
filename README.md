# 📊 COVID-19 Data Engineering Project

## 📝 Overview
This project analyses COVID-19 data using AWS services to provide insights and visualizations. The project involves ingesting data from various sources, transforming it, and making it available for analysis and reporting. 

## 🛠️ Tools and Steps

### Tools:
- 🪣 **Amazon S3**: Storage for raw and processed data.
- 🕵️ **AWS Glue Crawler**: Discover and catalog metadata about the data stored in S3.
- 🔍 **Amazon Athena**: Interactive query service for analyzing data in S3.
- 🧩 **AWS Glue**: ETL service for data transformation.
- 📊 **Amazon Redshift**: Data warehousing service for complex queries and analysis.
- 📈 **Tableau / Power BI**: Visualization tools for data reporting and dashboard creation.
- 🌐 **Amazon VPC**: Ensures secure network setup.

### Steps:

### 🔄 Data Ingestion
- **Amazon S3**: Ingest raw COVID-19 data from various sources like Johns Hopkins, The New York Times, and the COVID Tracking Project into S3.

### 🧩 Data Processing
- **AWS Glue Crawler**: Discover and catalog the data in S3, making it available for querying.
- **AWS Glue**: Transform raw data into a structured format suitable for analysis.

### 🔍 Data Analysis
- **Amazon Athena**: Perform SQL queries on the processed data directly in S3 to generate insights.
- **Amazon Redshift**: Use for more complex queries and analysis that require a data warehouse.

### 📊 Data Visualization
- **Tableau / Power BI**: Connect to Amazon Redshift or Athena to create interactive dashboards and visualizations.

## 📊 Data Details

### Global Coronavirus (COVID-19) Data
- **Table**: enigma_jhu
  - **Description**: Tracks confirmed COVID-19 cases globally.
  - **Source**: Johns Hopkins
  - **Provider**: Enigma

### Coronavirus (COVID-19) Data in the United States
- **Tables**: nytimes_states, nytimes_counties
  - **Description**: Tracks confirmed cases and deaths in the US by state and county.
  - **Source**: The New York Times
  - **Provider**: Rearc

### Coronavirus Disease (COVID-19) Testing Data
- **Tables**: covid_testing_states_daily, covid_testing_us_daily, covid_testing_us_total
  - **Description**: Tracks testing data, including number of tests conducted and test results.
  - **Source**: COVID Tracking Project
  - **Provider**: Rearc

### USA Hospital Beds – COVID-19
- **Table**: hospital_beds
  - **Description**: Data on hospital beds and their utilization in the US.
  - **Source**: Definitive Healthcare
  - **Provider**: Rearc

### COVID-19 Open Research Dataset (CORD-19)
- **Description**: A collection of research articles about COVID-19, SARS-CoV-2, and related coronaviruses, enriched with annotations from Amazon Comprehend Medical.

### Lookup Tables
- **country_codes**: Lookup table for country codes.
- **county_populations**: Lookup table for population data for each county based on recent census data.
- **us_state_abbreviations**: Lookup table for US state abbreviations.

## 🔗 Additional Resources
For more information and detailed instructions on using the AWS COVID-19 data lake, refer to the [AWS Big Data Blog post](https://aws.amazon.com/blogs/big-data/a-public-data-lake-for-analysis-of-covid-19-data/).

## 📝 Conclusion
This project sets up a comprehensive data pipeline using AWS services for ingesting, processing, analyzing, and visualizing COVID-19 data. The setup enables users to gain insights and create detailed reports and dashboards to understand and track the pandemic's impact effectively.

## 📷 Architecture Diagram
This diagram outlines the flow of data from ingestion to visualization using various AWS services, ensuring secure, scalable, and efficient data analysis.

## 📸 Screenshots
![Screenshot 2024-07-22 114447](https://github.com/user-attachments/assets/523b7513-c80f-43f2-bd69-74536004236c)
![Screenshot 2024-07-22 114550](https://github.com/user-attachments/assets/dd6ee3ac-682d-419e-9b1f-31a5fdc14d67)


