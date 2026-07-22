# World Layoffs Data Cleaning and Exploratory Analysis

## Project Overview

This project demonstrates data cleaning and exploratory data analysis in MySQL using a global layoffs dataset containing approximately 2,000 records.

The raw dataset included duplicate records, inconsistent text values, missing data, and formatting issues. The data was cleaned and standardized before being analyzed to identify patterns in layoffs across companies, industries, countries, dates, and funding stages.

## Tools Used

* MySQL
* SQL
* MySQL Workbench

## Project Files

* `layoffs.csv` — Original layoffs dataset
* `data_cleaning_project.sql` — SQL queries used to clean and standardize the dataset
* `exploratory_analysis_project.sql` — SQL queries used to analyze layoffs trends and patterns

## Data Cleaning Process

The cleaning process included:

* Removing duplicate records
* Trimming unnecessary spaces
* Standardizing company, industry, and country values
* Converting date values into a consistent format
* Handling NULL and blank values
* Removing temporary or irrelevant columns

## Exploratory Data Analysis

The exploratory analysis examined:

* Companies with the highest total layoffs
* Industries most affected by layoffs
* Countries with the highest number of layoffs
* Layoffs by company funding stage
* Layoff trends by year and month
* Companies that reported laying off their entire workforce
* Rolling totals and rankings using SQL window functions

## Skills Demonstrated

* SQL data cleaning
* Common table expressions
* Window functions
* Aggregate functions
* Data standardization
* NULL-value handling
* Grouping and filtering
* Ranking and time-based analysis

## Repository Purpose

This repository is part of my data analytics and data science portfolio. It demonstrates my ability to transform raw relational data into a clean dataset and use SQL to identify business-relevant patterns.
