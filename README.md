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

Part-II:- This project performs Exploratory Data Analysis (EDA) using SQL on a layoffs dataset that contains information about companies, industries, countries, funding stages, and employee layoffs over time.

The goal was to uncover patterns, trends, and insights such as which companies, industries, and years had the highest layoffs, as well as to rank top companies by layoffs each year.

explosure
I explored the layoffs dataset in SQL by first identifying maximum layoffs, companies with 100% workforce cuts, and the overall timeline. Then, I aggregated layoffs by company, industry, country, and funding stage to compare their impact. I also analyzed year-wise and month-wise layoffs, created rolling totals to track cumulative layoffs over time, and used window functions (DENSE_RANK) to rank the top 5 companies with the highest layoffs each year

Insights
The analysis showed that 2020 had the highest layoffs, mainly in industries hit hard by COVID-19 such as travel, ride-hailing, and food delivery, with Uber, Booking.com, and Airbnb among the worst affected. In 2021, layoffs were still high but spread across sectors like tech, real estate, and edtech, with Bytedance, Katerra, and Zillow leading. Overall, the United States recorded the highest layoffs, and the monthly trend highlighted how layoffs surged during peak pandemic periods before stabilizing.

This project demonstrates the use of SQL for:
1. Data aggregation & summarization
2. Trend analysis using GROUP BY & window functions
3. Ranking insights with DENSE_RANK()
4. Business interpretation of workforce trends

The analysis provides a clear picture of layoff patterns and showcases how SQL can be used for real-world EDA.

MySQL EDA output
https://drive.google.com/file/d/1hZFrTP0ZglelTSaiWBCux6djPM8Pw9dL/view?usp=drive_link

Oracle PL mini project 

Output image


