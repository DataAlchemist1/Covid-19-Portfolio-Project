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
