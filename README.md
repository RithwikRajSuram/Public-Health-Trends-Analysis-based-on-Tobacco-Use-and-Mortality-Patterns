# Public Health Trends Analysis: Tobacco Use and Mortality Patterns

## Project Overview
This project analyzes public health trends using Python by exploring tobacco-use survey data and monthly provisional mortality data from 2020 to 2023. The goal of this project is to identify patterns in tobacco-use indicators, evaluate data quality, examine mortality trends, and visualize relationships between major causes of death.

This project demonstrates core health data analytics skills including data cleaning, exploratory data analysis, missing value assessment, outlier detection, trend visualization, and public health interpretation.

## Objective
The main objective of this project is to use Python-based exploratory data analysis to better understand how public health indicators vary across time and how mortality outcomes differ by cause of death.

The analysis focuses on:

- Tobacco-use data trends and distributions
- Survey data quality and missing values
- Monthly mortality patterns from 2020 to 2023
- COVID-19, heart disease, diabetes, respiratory disease, and all-cause death trends
- Relationships between selected mortality outcomes
- Outlier detection in numeric public health variables

## Datasets Used

### 1. Behavioral Risk Factor Tobacco Use Dataset
This dataset contains tobacco-use related public health survey information. It includes variables such as year, sample size, and reported tobacco-use data values.

Key fields used:

| Column | Description |
|---|---|
| `YEAR` | Survey year |
| `Data_Value` | Reported tobacco-use measure or percentage |
| `Sample_Size` | Number of survey observations |

### 2. Monthly Provisional Counts of Deaths Dataset, 2020–2023
This dataset contains monthly death counts by cause of death.

Key fields used:

| Column | Description |
|---|---|
| `Year` | Year of recorded deaths |
| `Month` | Month of recorded deaths |
| `All Cause` | Total deaths from all causes |
| `Natural Cause` | Deaths due to natural causes |
| `COVID-19 (Underlying Cause of Death)` | Deaths where COVID-19 was the underlying cause |
| `Diseases of Heart` | Deaths due to heart disease |
| `Diabetes Mellitus` | Deaths due to diabetes |
| `Accidents (Unintentional Injuries)` | Deaths due to unintentional injuries |
| `Chronic Lower Respiratory Diseases` | Deaths due to chronic lower respiratory diseases |

## Tools and Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
