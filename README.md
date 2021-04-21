# butler-groupD-project1

## Project Title:
Did National Happiness Levels Impact COVID-19 Mortality Rates?

## Team Members:
Anthony Kerins, Sydni Pierce

## Project Description/Outline:
This project will use 2019 happiness statistics pulled from the 2021 World Happiness Report to investigate whether pre-pandemic measures of national happiness correlated with COVID-19 mortality rates in 2020 on a national level.

## Research Questions to Answer:
* Did countries with higher pre-pandemic national happiness levels have lower COVID-19 mortality rates in 2020?
* Which measures of national happiness were most strongly correlated with COVID-19 mortality rates?
* How does healthy life expectancy at birth factor into COVID-19 mortality rates?

## Datasets to Be Used:
World Happiness Report 2021
* [Data Panel](https://happiness-report.s3.amazonaws.com/2021/DataPanelWHR2021C2.xls)
* [Mortality Data](https://happiness-report.s3.amazonaws.com/2021/MortalityDataWHR2021C2.xlsx)

## Rough Breakdown of Tasks:
* Import and read 2021 World Happiness Report Data Panel and Mortality Data files.
* Explore and clean the data (if needed) - view the files as tables and pull stats on the tables (row count, etc.).
* Pull 2019 records for each country from the Data Panel and merge with the Mortality Data on country.
* Create scatter plots of individual happiness statistics vs. COVID-19 mortality rate (each dot equals a country) to scan for potential relationships.
* Run a linear regression on correlations that look promising.
