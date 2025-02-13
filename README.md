# World Happiness Report, Passenger Data, and Supermarket Sales Analysis

## Overview

This repository contains data analysis and SQL database creation tasks based on four datasets:

- World Happiness Report

- Passenger Demographics 

- Survival Data

- Supermarket Sales Data

The analysis includes basic data exploration, statistical analysis, data filtering, merging datasets, survival analysis, and database creation with SQLite3.

## Datasets

- WorldHappinessReport.csv: Contains happiness scores and related factors for different countries.

- passenger_demographics.csv & passenger_survival.csv: Includes passenger details and survival information from a historical dataset.

- supermarket_sales.csv: Records information of supermarket transactions.

## Tasks Completed

### 1. Basic Data Exploration (World Happiness Report)

- Loaded the dataset using Pandas.

- Displayed column names, first & last 10 rows, random samples, and summary statistics.

- Counted missing values in each column.

### 2. Basic Data Statistics (World Happiness Report)

- Computed mean, median, and standard deviation of the Happiness Score.

- Identified the happiest and least happy countries.

- Analyzed Healthy Life Expectancy, GDP per Capita, and Corruption Perceptions.

- Filtered data based on Social Support, Freedom, and Generosity.

### 3. Passenger Data Analysis

- Merged passenger_demographics.csv and passenger_survival.csv on PassengerId.

- Checked for duplicates and performed data consistency checks.

- Analyzed survival rates based on gender, class, age, family size, embarkation point, and fare.

- Applied binning techniques for age and family size analysis.

### 4. Supermarket Sales Database with SQLite3

- Created a relational database with three tables:

   - Branches Table (Branch details)

   - Products Table (Product categories)

   - Orders Table (Sales transactions)

- Executed queries to:

   - Identify top-selling products

   - Calculate branch-wise revenue and total sales

   - Analyze customer demographics

   - Find the highest quantity sold in a single order

   - Detect duplicate invoices


Acknowledgments

This project is part of a data analysis and SQL assignment. The dataset sources include publicly available reports and transaction data.
