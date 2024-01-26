# COVID-19 Death Project
## About This Project
This project involves the cleaning and exploration of a dataset tracking COVID-19 deaths worldwide. The goals of the project are to prepare the raw dataset for analysis by handling missing data, correcting data inconsistencies, and transforming data formats. With a refined, analysis-ready dataset, we can gain better insights into the impact and trends related to COVID-19 mortality around the globe. The final cleaned dataset may be used to build interactive visualizations, models, or applications to share findings from the data.
# Data Exploration Process

1. Import Raw Data
   - Import CSV files into SQL database tables for CovidDeaths and CovidVaccinations data

2. Initial Data Exploration
   - Query tables to view data schemas, summary stats, examine raw data quality issues 

3. Data Cleaning
   - Handle null values
   - Standardize formats for location, date columns 
   - Correct anomalies and outliers
   - Address integrity constraints between tables

4. Calculate Key Metrics
   - Total Cases vs Total Deaths (% death rate)
   - Cases/Deaths per Population 
   - Running totals for vaccinations 

5. Aggregate & Summarize
   - Rank countries by infection rates, death rates
   - Breakdown numbers by continent 
   - Worldwide totals over time
   
6. Join Datasets
   - Join the CovidDeaths and CovidVaccinations tables
   - Match on location and date to analyze vaccination rate vs case data
   
7. Advanced Analysis
   - Use CTEs and Temp Tables to calculate percentages, run totals
   - Create views to store data for visualizations
   
8. Visualize Data Insights
   - Build charts, and dashboards in Power BI
   - Interactive analysis of key metrics and trends

The major tasks involved are assessing data quality, resolving inconsistencies, handling missing data, standardizing formats, and ensuring integrity for downstream usage. The final clean dataset will enable more accurate analytics.

# Potential Questions To Be Answered
1. What global trends can be observed in Covid-19 mortality over time?
-- Tracking infection rates and death rates by location and date could reveal spreads, peaks, and declines.
   
2. Which locations have seen the highest death rates relative to their populations?
-- Calculating death percentages by location would highlight the hardest-hit areas.
   
3. How do death rates differ across geographic regions and between rural vs urban areas?
-- Grouping and comparing locations could reveal variances.
   
4. When did different countries reach peak death rates?
-- Charting daily/weekly fluctuations could pinpoint peaks.
   
5. How strong is the correlation between infection rates and mortality rates?
-- Statistical analysis between infections and deaths by date/location may show patterns.
   
6. How effective were public health measures in reducing deaths?
-- Changes in policy dates could be combined with death rate time series analysis.
