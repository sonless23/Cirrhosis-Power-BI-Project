[hepatitis_C_EHRs_Japan.csv](https://github.com/user-attachments/files/19348305/hepatitis_C_EHRs_Japan.csv)# Relationship Between Liver Cirrhosis and Various Clinical Indices
## Table of Contents
•	Project Overview

•	Tools Used

•	Data Sources

•	Dataset

•	Data Cleaning

•	Data Analysis

•	Findings

•	Lessons

•	Limitations
## Project Overview/Objective
This project analyzes and visualizes the relationship between liver cirrhosis and various clinical indices, such as glucose levels, cholesterol levels, BMI, and age. The objective is to identify patterns in how these factors correlate with cirrhosis development in patients.
 
## Tools Used
•	Power BI (for data transformation and visualization)
## Data Sources
•	Hepatitis dataset obtained from Kaggle

Find the dataset attached in the repository

## Dataset
The dataset consists of 123 records and 13 columns, including:

•	cirrhosis (1 = cirrhosis, 0 = no cirrhosis)

•	age

•	sex (1 = male, 2 = female)

•	cholesterol

•	triglyceride

•	HDL & LDL cholesterol levels

•	BMI

•	ALT, AST (liver function tests)

•	glucose levels

•	serogroup01 (missing values present, not used in analysis)
## Data Cleaning and Transformation
In Power Query (Power BI), I:

•	Changed data types for some columns.

•	Binned numerical columns such as age, glucose levels, cholesterol, and BMI for better visualization.

•	The serogroup01 column was excluded from the analysis due to the presence of missing values.
## Data Analysis
Using Power BI visualizations, the following analyses were conducted:

•	**Cirrhosis by sex:** Examined differences in cirrhosis prevalence between males and females.

•	**Cirrhosis by glucose levels:** Analyzed glucose levels and their impact on cirrhosis.

•	**Cirrhosis by BMI:** Observed trends between body mass index and cirrhosis occurrence.

•	**Cirrhosis by age levels:** Identified age groups most affected by cirrhosis.

•	**Cirrhosis by cholesterol levels:** Evaluated cholesterol variations in relation to cirrhosis.
## Findings
•	**Higher Cirrhosis Prevalence in Females:** Females had a higher percentage of cirrhosis cases compared to females.

•	**Glucose Levels and Cirrhosis:** Higher glucose levels were associated with a greater likelihood of cirrhosis. It also seemed that particularly low levels of glucose is also associated with higher likelihood of cirrhosis.

•	**BMI and Cirrhosis:** There was a varying pattern, with higher cirrhosis prevalence in both lower and higher BMI ranges. People with BMI between 20 and 27.5 had the lowest prevalence of cirrhosis.

•	**Age and Cirrhosis:** People in their fifties (i.e. aged between 50 to 60) had higher cirrhosis prevalence than those aged 60 and above.

•	**Cholesterol and Cirrhosis:** No clear trend was observed, but certain cholesterol ranges had higher cirrhosis rates.

![LIVER CIRRHOSIS POWER BI DASHBOARD](https://github.com/user-attachments/assets/ef5557e6-de68-4edf-9e16-4667e1f4e61d)

## Lessons
•	Data binning and visualization techniques helped uncover meaningful patterns in the dataset.

•	Certain risk factors (such as high glucose and age) showed a clearer link to cirrhosis, whereas others (like cholesterol) required further analysis.
## Limitations
•	Small sample size (123 patients) limits generalizability.

•	Some missing values (e.g., in serogroup01 column) could affect analysis.

•	The serogroup01 column was not used due to missing values.

•	Dataset source accuracy was not validated, so findings should be interpreted with caution.
________________________________________
This project serves as a demonstration of data analysis and visualization using Power BI to explore clinical factors associated with liver cirrhosis.
