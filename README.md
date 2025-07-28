# CarSharing-Report-with-SQL-Queries
## Overview
This repository contains SQL queries and documentation for analyzing a car-sharing dataset. The dataset includes information about customer demand rates, weather conditions, and temperature data collected on an hourly basis between January 2017 and August 2018.
## Files
- SQL_queries.sql: Contains SQL queries used to analyze the dataset and answer specific business questions.
- Data_Model.ERD.png: Entity-relationship diagram (ERD) illustrating the data model and relationship between tables.
- Data_Dictionary.md: Documentation describing the structure and contents of each table in the dataset.
- README.md: This file provides an overview of the repository and instructions for accessing and usin the SQL queries.

Click 👉[here](https://drive.google.com/drive/folders/1EfqSz61tbq_2HyQCu0PyZoaM-xpZk0KR?usp=sharing)👈 to see these files.

## SQL Queries
1. Highest demand rate in 2017:
- Query to find the exact date and time when the highest demand occurred in 2017.
2. Average demand rates by Weekday, Month, and Season; Query to;
- (2A) Calculate the weekday, month, and season with the highest average demand in 2017.
- (2B) Calculate the weekday, month, and season with the lowest average demand in 2017.
3. Hourly demand rates for the selected weekday(s) in 2017:
- Query to calculate the average demand for each hour of the selected weekday(s) from (b).
4. Weather analysis for 2017:
- (4a) Determine whether 2017 was mostly cold, mild, or hot, based on temperature categories.
- (4b) Identify the most frequent weather condition (from the weather column).
- (4c) Provide monthly statistics for:
- (i) Wind speed: average, highest, and lowest
- (ii) Humidity: average, highest, and lowest
- (4d) Calculate the average demand for cold, mild, and hot weather categories.
5. Weather analysis for the highest demand month in 2017:
- (5a) Identify the month with the highest average demand in 2017.
- (5b) Repeat the weather-related analysis from (4) for that month only (i.e., cold/mild/hot classification, wind speed, humidity, and average demand).

## Instructions
1. Clone or download this repository to your local machine.
2. Open the SQL_queries.sql file to view the SQL queries.
3. Execute the SQL queries in your preferred SQL database management system (e.g., MySQL workbench, SQLite).
4. Review the results and analysis provided by each query.
5. Refer to the Dta_Dictionary.md file for descriptions of table structures and column definitions.
  
## Data Source
The original dataset was obtained froma car-sharing company and incules hourly data on customer demand rates, weather conditions, and temperature. Due to privacy considerations, the dataset has been anonymized and sanitized.

## Author
[Precious Okpala](https://github.com/Precious-Okpala)
