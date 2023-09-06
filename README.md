# Data-Science-job-postings-on-Glassdoor-Performing-Exploratory-Data-Analysis-
The primary goal of this project is to conduct a thorough data cleaning process and perform exploratory data analysis (EDA) on a dataset.

![2023_blog-home-featured-ani_728x466](https://github.com/S-Tanwar/Data-Science-job-postings-on-Glassdoor-Performing-Exploratory-Data-Analysis-/assets/95356553/0846816b-4a10-4fb5-9bb5-60487e829ed3)

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

## My Findings
During the exploratory data analysis (EDA) phase, I made several noteworthy observations:

1. Size of Companies:
The majority of companies in the dataset have between 51 to 200 employees, with 135 companies falling into this category.
Companies with 1001 to 5000 employees and 1 to 50 employees are also relatively common, with 104 and 86 companies, respectively.
The least common size category is companies with 5001 to 10,000 employees, with only 61 companies falling into this group.

2. Type of Ownership:
The most common type of ownership is "Company - Private," with 397 companies falling into this category.
"Company - Public" is the second most common type of ownership, with 153 companies.
Other types of ownership, such as "Nonprofit Organization" and "Subsidiary or Business Segment," are less common.

3. Industry:
The dataset covers a wide range of industries, with the top three being Biotech & Pharmaceuticals (66 companies), IT Services (61 companies), and Computer Hardware & Software (57 companies).
Many other industries are represented, including Aerospace & Defense, Enterprise Software & Network Solutions, and Consulting.

4. Sector:
The most common sector is Information Technology, with 188 companies falling into this category.
Other significant sectors include Business Services (120 companies), Biotech & Pharmaceuticals (66 companies), and Aerospace & Defense (46 companies).

5. Revenue:
The dataset includes companies with a diverse range of revenue levels.
The most common revenue range is 100 to 500 million (USD) with 94 companies.
Some companies have very high revenue levels, such as 10+ billion (USD), while others have lower revenues, such as Less than 1 million (USD).

6. Location:
The dataset includes companies from various locations, with San Francisco, CA having the highest representation (69 companies).
Other notable locations include New York, NY (50 companies), Washington, DC (26 companies), and Boston, MA (24 companies).

7. Skewness and Kurtosis for Rating:
Skewness value is approximately 0.0187, indicating a nearly symmetric distribution of ratings with a slight right (positive) skew.
Kurtosis value is approximately -0.44, suggesting a platykurtic distribution with thinner tails compared to a normal distribution.

![graph 8](https://github.com/S-Tanwar/Data-Science-job-postings-on-Glassdoor-Performing-Exploratory-Data-Analysis-/assets/95356553/667105fa-c475-43fb-8873-dc217f79c3d9)

9. Skewness and Kurtosis for High_Salary_in_dollar (Upper limit of salary):
Skewness value is approximately 1.09, indicating a moderate right (positive) skew in salary distribution.
Kurtosis value is approximately 2.41, suggesting a leptokurtic distribution with heavier tails and a more peaked shape than a normal distribution.

![graph 7](https://github.com/S-Tanwar/Data-Science-job-postings-on-Glassdoor-Performing-Exploratory-Data-Analysis-/assets/95356553/5204ce23-198b-4737-b01d-46bd5c4f0203)

10. Outliers for High_Salary_in_dollar and Rating:
Outliers were identified for both high salaries and ratings, which may require further investigation for their impact on the analysis.

![graph 6](https://github.com/S-Tanwar/Data-Science-job-postings-on-Glassdoor-Performing-Exploratory-Data-Analysis-/assets/95356553/3d96de1d-abc7-48fb-93d0-f9b43008481f)

11. Relationship between Rating and Salary:
A weak positive relationship (correlation coefficient of 0.0099) was observed between employee ratings and high salaries.

![graph 5](https://github.com/S-Tanwar/Data-Science-job-postings-on-Glassdoor-Performing-Exploratory-Data-Analysis-/assets/95356553/6af3f1a2-4464-44e9-83a8-d6dd9d9c6263)

11. Salary Variation Across Locations:
Salaries exhibited significant variation across different locations, with high-paying and low-paying locations identified.

12. Salary with Respect to Industry:
Industry had a noticeable impact on salary levels, with variations observed among different industries.

![graph 4](https://github.com/S-Tanwar/Data-Science-job-postings-on-Glassdoor-Performing-Exploratory-Data-Analysis-/assets/95356553/630aa781-5dcc-4086-9308-902d18d39dc4)

13. Rating Variation by Sector:
Employee ratings varied across different sectors, with some sectors having higher average ratings than others.

![graph 3](https://github.com/S-Tanwar/Data-Science-job-postings-on-Glassdoor-Performing-Exploratory-Data-Analysis-/assets/95356553/2500ce08-6675-43c7-ac1d-6bd8c36f3a0a)

14. Relationship between Rating and Type of Ownership:
Type of ownership was found to influence employee ratings, with certain ownership types associated with higher average ratings.

![graph 2](https://github.com/S-Tanwar/Data-Science-job-postings-on-Glassdoor-Performing-Exploratory-Data-Analysis-/assets/95356553/abef54fa-5565-4300-84cb-6b7ce5a77714)


15. Companies with the Most Job Postings:
Companies with the highest number of job postings were identified, indicating active recruitment and potential job opportunities.

16. Comparison of Industry with Respect to Salary and Rating:
Industries that offered the highest average salaries and received the highest ratings from employees were identified.

![graph 1](https://github.com/S-Tanwar/Data-Science-job-postings-on-Glassdoor-Performing-Exploratory-Data-Analysis-/assets/95356553/e8478ff4-f540-4010-b26c-e8c4dbd9d280)
