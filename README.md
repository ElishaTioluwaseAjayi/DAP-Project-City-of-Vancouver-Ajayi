<h1 align="center">City of Vancouver DAP Design for Vancouver Parks</h1>
<p align="center">
Elisha Tioluwase Ajayi (2228686) <br>
University Canada West<br>
BUSI 653, Section 07<br>
Instructor: Mahmood Mortazavi Dehkordi<br>
</p>

___

# Project Description: Descriptive Analysis of Rental Standards
In this assignment I will be describing the details of the City of Vancouver project mainly about the Data Analytic Platform (DAP) implementation (the datasets used and the various derivations and DAP design using the datasets I selected. For this assignment I used the website [City of Vancouver Open Data Portal](https://opendata.vancouver.ca/explore/dataset/property-tax-report/table/?sort=-tax_assessment_year) for getting some open source available datasets for various segments related to the Vancouver City operations. ​This dataset contains information on properties from BC Assessment (BCA) and City sources from 2020. To limit the size of individual datasets, we segmented the property tax data into multiple datasets.  See ​all ​property tax datasets​ for data since 2006. This data in City systems is updated in the normal course of business, however priorities and resources determine how fast a change in reality is reflected in the database. Accuracy is dependent on the matching of records between multiple agencies including non-City sources.

## Project Title: Understanding Yearly Patterns of Rental Standards
The primary need of this project is to conduct a descriptive and Exploratory Analysis of Vancouver City rental standards based on the datasets taken from [City of Vancouver Open Data Portal](https://opendata.vancouver.ca/explore/dataset/property-tax-report/table/?sort=-tax_assessment_year). The hope with this question was to gain insight into how accessible the rental properties are in Vancouver City. As informed earlier the dataset select by me is about the “Rental Standards”. Here the descriptive metric Ajayi planned to analyse is about “What is the percentage of number of available Rental  Business Operators in each Geo-areas of Vancouver?”  For this the dataset select is the “Rental Standards” from the [City of Vancouver Open Data Portal](https://opendata.vancouver.ca/explore/dataset/property-tax-report/table/?sort=-tax_assessment_year) website. This dataset has information of the Business operator, their url, the business address details(like Business Operators, Details url, street name and others), the outstanding units and total units. I selected the dataset related to rentals in Vancouver. I selected to work on the rental agencies in different areas of Vancouver. This second part of the DAP design includes the next process of DAP that is once the needed analysis data is available after Glue pipeline design. This included multiple details and segments discussed below.
## Project Objective:
* Data Analysis Process (DAP) is the methodical way of viewing data and discovering useful insights or patterns, helping to make decisions.
* It takes the form of steps including data collection, profiling, data cleaning, transformation, visualization, and ending with actionable conclusions.
* The dataset taken by me is about the  “Rental Stanadards” segment of the “Property” module of the Vancouver city portal.
* In this we have key features like the ‘Business Operators’, ‘Total Units’, ‘Total Outstanding Units’, ‘Street Number’,  ‘Street Name’ and other details.
* From this, the main objective is to do descriptive analysis on “What is the percentage of number of available Rental  Business Operators in each Geo-areas of Vancouver?” using this, we can further analyze the population segmentation around these areas and other details.
* We aldo do an exploratory analysis on question of “How many Business Operators operate in more than one geo location and how many units they manage?” to further analyse and find any trends available.
## Datasets
* There is one datasets which I will be using here.
* The dataset is **"Rental Standards"**, it contains information about the Vancouver Board of Rental Properties maintained throughout the City of Vancouver.
* This dataset provides information of the areas and available units in them. Additional details are found in related dataset.
* This data set contain the information of data columns like:
[rental-standards-current-issues.xlsx](https://github.com/user-attachments/files/18138189/rental-standards-current-issues.xlsx) contains the information of this dataset.
## Methodology:
* The process of DAP designing and implementation is complex.
* This involves 3 stages namely:
### Part 1 - [Descryptive Analysis of Rental Standards of Vancouver City](https://elishatioluwaseajayi.github.io/Descriptive-Analysis-of-Rental-Standards/)
* The dataset taken by me is about the  “Rental Stanadards” segment of the “Property” module of the Vancouver city portal.
* In this we have key features like the ‘Business Operators’, ‘Total Units’, ‘Total Outstanding Units’, ‘Street Number’,  ‘Street Name’ and other details.
* The descriptive analysis is on “What is the percentage of number of available Rental  Business Operators in each Geo-areas of Vancouver?”.
#### Dap Design
![image 001](https://github.com/user-attachments/assets/a685bf44-47b3-41cf-ba08-f370fbf36158)<br>
The above image displays the DAP design we are implementing for the descyptive analysis.
#### Descriptive  Question for Analysis
![image 000](https://github.com/user-attachments/assets/453178f7-43f4-4798-8e38-e613f1f775cf)<br>
The above images displays the descryptive analysis of our DAP model.
#### Step 1: Data Ingestion
This step explains about the Data ingestion into AWS Environment
#### Step 2: Data Profiling
This step explain the data profiling in the AWS environment.
#### Step 3: Data Cleaning 
This step explaing the Data cleaning done using the AWS DataBrew service.
#### Step 4: Data Pipeline Design 
This step explain the process of designing a ETL pipeline to transform raw data into structured data.
### Part 2 - [Exploratory Analysis of Rental Standards of Vancouver City](https://elishatioluwaseajayi.github.io/Exploratory-Analysis-of-Rental-Standards/)
* The dataset taken by me is about the  “Rental Stanadards” segment of the “Property” module of the Vancouver city portal.
* In this we have key features like the ‘Business Operators’, ‘Total Units’, ‘Total Outstanding Units’, ‘Street Number’,  ‘Street Name’ and other details.
* The descriptive analysis is on “How many Business Operators operate in more than one geo location and how many units they manage?”.
#### Dap Design
![image 001](https://github.com/user-attachments/assets/a685bf44-47b3-41cf-ba08-f370fbf36158)<br>
The above image displays the DAP design we are implementing for the descyptive analysis.
#### Descriptive  Question for Analysis
![image 000-1](https://github.com/user-attachments/assets/f2b6ef1c-ed19-4860-8f4e-781095e0080f)<br>
The above images displays the exploratory analysis of our DAP model.
#### Step 1: Data Ingestion
This step explains about the Data ingestion into AWS Environment
#### Step 2: Data Profiling
This step explain the data profiling in the AWS environment.
#### Step 3: Data Cleaning 
This step explaing the Data cleaning done using the AWS DataBrew service.
#### Step 4: Data Pipeline Design 
This step explain the process of designing a ETL pipeline to transform raw data into structured data.
### Part 3 - [Other DAP Procedures of Data Enriching, Protection, Governance and Observability](https://elishatioluwaseajayi.github.io/DAP-Model-Advanced-Operations/)
This step involves the 4 major steps namely:
#### Step 1: Data Enriching
Data enrichment in data management is all about augmenting raw data with relevant context and information that provides more value for analytical purposes.<br>
This cleanses the data and transforms it to provide meaningful insights, which again are useful to make better decisions. 
#### Step 2: Data Protection
In AWS, one can protect sensitive data by encrypting it to protect its confidentiality and security.<br>
AWS KMS provides a centralized control point for encryption keys so that users can create, manage, and use them to perform encryption and decryption automatically and with control over access to the keys using IAM policies.<br>
It improves data protection to be compliant with security standards.
#### Step 3: Data Governance 
Data governance is the discipline for establishing, implementing, and maintaining the structure for data across the enterprise.<br>
This means defining data quality, privacy, security, and compliance with regulatory standard policies, roles, and procedures.<br>
Starting with creating access controls, auditing data usage, enabling encryption capabilities for your data, and using features such as AWS Glue Data Catalog for managing and cataloging metadata, data governance in AWS is a combination of setup, management, and maintenance.
#### Step 4: Data Observability 
The real-time performance and health of the data platform in the rental standards domain is visualized using the data observability dashboard displayed in AWS CloudWatch.<br>
A customized dashboard tracks key metrics, including bucket storage utilization, number of objects in buckets, and associated estimated charges, giving a full view of data operations. 
