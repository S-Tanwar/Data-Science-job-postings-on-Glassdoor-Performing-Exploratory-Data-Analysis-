# Data-Science-job-postings-on-Glassdoor-Performing-Exploratory-Data-Analysis-
The primary goal of this project is to conduct a thorough data cleaning process and perform exploratory data analysis (EDA) on a dataset.

## Introduction
As a data analyst, I embarked on a journey to conduct comprehensive data cleaning and exploratory data analysis (EDA) to improve data quality and unveil hidden patterns within a dataset. This project aims to provide valuable insights and facilitate informed decision-making. In this blog post, I will walk you through the entire process, from the dataset explanation to the findings.

## Goal
The primary goal of this project is to conduct a thorough data cleaning process and perform exploratory data analysis (EDA) on a dataset. By doing so, I aim to improve data quality, identify patterns, and facilitate informed decision-making for future analysis. Through this project, I showcase my proficiency in data preprocessing and analytical techniques.

## Explain the Dataset 
The dataset I worked with comprises 15 columns, each serving a specific purpose: (Link of the dataset)
1. Job Title: The job title associated with each entry.
2. Salary Estimate: The salary range for each job position.
3. Rating: Company rating on a scale of 0 to 5.
4. Company Name: The name of the hiring company.
5. Location: The location of the job opportunity.
6. Size: The size category of the company in terms of employees.
7. Founded: The year the company was founded.
8. Type of Ownership: The ownership type of the company.
9. Industry: The industry to which the company belongs.
10. Sector: The sector to which the company belongs.
11. Revenue: The revenue of the company.
12. Competitors: Competitor companies.

## Explaining the Process
My data cleaning and EDA process involved several key steps:
1. Importing Libraries: I began by importing essential Python libraries, including pandas, numpy, matplotlib, and seaborn, to assist in data manipulation and visualization.

2. Reading the File: I loaded the dataset from the provided CSV file into a pandas DataFrame for further analysis.

3. Handling Missing Values: I checked for missing values within the dataset and found none, ensuring that the data was complete and ready for analysis.

4. Data Transformation:
-- I dropped the 'index' column as it served as a serial number and had the potential to affect the analysis.
-- I extracted the lower and upper salary limits from the 'Salary Estimate' column and created new columns to represent these values.

5. Data Cleaning and Transformation for Specific Columns:
-- I processed columns such as 'Job Title', 'Company Name', 'Size', 'Type of Ownership', 'Industry', 'Sector', and 'Revenue' to handle missing values and improve data quality.
