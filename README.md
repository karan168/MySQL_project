# MySQL_project

Part-I:- This project focuses on data cleaning and preprocessing of a dataset containing company layoff information. The dataset includes details such as company name, location, industry, number of employees laid off, percentage laid off, date, stage of funding, country, and funds raised.
The objective was to clean, standardize, and prepare the dataset for further analysis by ensuring consistency, accuracy, and reliability of the information.

Steps Performed
1. Created a staging table to preserve raw data.
2. Removed duplicates using ROW_NUMBER() with PARTITION BY.
3. Standardized text fields – trimmed company names, unified industry names, and fixed country formatting (e.g., United States. → United States).
4. Formatted dates from text to SQL DATE format.
5. Handled missing values – replaced blanks with NULL, filled missing industries using company information, and dropped irrelevant rows.
6. Dropped helper columns after data cleaning.

Outcomes
1. After cleaning, you obtained a refined dataset (as seen in your screenshot) where:
2. Companies, industries, and countries are properly standardized.
3. Dates are in correct YYYY-MM-DD format.
4. Duplicate and irrelevant rows are removed.
5. Missing values are either filled or dropped, ensuring higher data quality.

The final output table is clean, structured, and analysis-ready, making it suitable for further insights such as:
1. Trend analysis of layoffs across industries.
2. Impact of company stage and funding on layoffs.
3. Country-wise or location-wise layoff comparisons.

MySQL data cleaning output 
https://drive.google.com/file/d/1U_PXlxoswFiuex-kNWSMpmOTtUcCh50v/view?usp=drive_link

Part-II:- 

MySQL EDA output
https://drive.google.com/file/d/1hZFrTP0ZglelTSaiWBCux6djPM8Pw9dL/view?usp=drive_link

Oracle PL mini project 

Output image


