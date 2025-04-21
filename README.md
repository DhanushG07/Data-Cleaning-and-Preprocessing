# Data Analyst Internship - Task 1: Data Cleaning and preprocessing  

## Overview
The repository contains my submission for task 1 of the Data analyst internship. The objective was to clean and perprocess a raw dataset by identifing and resolving common data quality issues including missing values, duplicate records, and incorrect data types 

## Dataset 
- **Name**: Netflix Moives and TV shows
- **Source**: [kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- **Format**: CSV

## Tools & Tenchnologies
- Python (Pandas, NumPY)
- Jupyter Notebook (Google Colab)
- Github

## cleaning & perprocessing steps
1. **Handle Missing Values**
 - Identifing missing values using '.isnull().sum()'
 - Dropped or filled nulls using '.drop()' or 'fillna()' based on ccolumn context
 
2. **Remove Duplicates**
 - Applied '.drop_duplicates()' to remove repeated entries

3. **Standardized Categorical Data**
 - Fixed inconsistencies in 'type', 'country', and 'rating' using '.str.lower().strip()
 - Replace inconsistent text entries with unified labels
 
4. **Data Format Consistency**
 - Converted 'data_added' to 'datatime' using 'pd.to_datatime()' to uniform 'DD-MM-YYYY' format

5. **Rename Columns**
 - Change column names to lowercase and replace space with underscores
   
6. **Corrected Data Types**
 - Ensure correct types for numeric ,text, and datetime field

## output

- 'Cleaned_dataset.csv': Final cleaned dataset
- 'task1_data_cleaning.ipynb': Notebook with all data cleaning steps

## Reponsitory Structure 

Data-Analyst-Internship-Task-1/
- raw_dataset.csv 
- cleaned_dataset.csv
- task1_data_cleaning.ipynb
- README.MD

## Author 
- **NAME**:Dhanush Guduru
- **DATE**: 21st April 2025
- **GITHUB**:[Dhanush Guduru](https://github.com/DhanushG07)



