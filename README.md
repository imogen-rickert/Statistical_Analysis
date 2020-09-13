# Statistical_Analysis

*Imogen Rickert*

*August cohort, Berlin, 13.09.20*

## Content
- [Project Description](#project-description)
- [Questions & Hypotheses](#questions-hypotheses)
- [Dataset](#dataset)
- [Database](#database)
- [Workflow](#workflow)
- [Organization](#organization)
- [Links](#links)

## Project Description
The purpose of this project was to practice statistical analysis using the iterative data analysis process.


## Questions & Hypotheses
The goal of this analysis was to identify the most important features of houses that affect the sale prices. 


## Dataset
I utilised the dataset: 'House Prices: Advanced Regression Techniques', located on Kaggle: https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data


## Workflow
I began by examining the dataset, then cleaned and manipulated it using Pandas. Since the dataset was very large, I selected several columns to subset, and worked with the subset for my analysis, instead of using the entire dataset. I checked descriptive statistics, conducted linear and multi-variate regression and utilised Seaborn to visualise my results. 

I felt that I could find additional variables which would help to better explain the variance in housing price, so I went back to the original dataset, created a new subset with additional variables, and ran further analyses. 


## Organization
This repository contains the following files:
- Notebooks:
    - house_prices.ipynb (for data cleaning and creating subsets)
    - statistical_analysis.ipynb (for data analysis)
- Datasets:
    - train.csv (original dataset from Kaggle)
    - houses_cleaned (full dataset after cleaning/manipulation)
    - houses_subset (first subset)
    - houses_subset2 (second subset)
