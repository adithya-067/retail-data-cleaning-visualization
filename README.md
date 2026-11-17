# Retail Transaction Data Cleaning and Visualization

A Data Science project focused on cleaning, preprocessing, analysing and visualizing real-world retail transaction data using Python.

## Project Overview

This project uses the Online Retail dataset from the UCI Machine Learning Repository to demonstrate practical data cleaning and visualization techniques.

The project involves identifying missing values, handling duplicate records, examining outliers, preprocessing transaction data and extracting meaningful business insights through visualizations.

## Objectives

- Identify and handle missing values.
- Detect and remove duplicate records.
- Identify invalid transactions and unusual values.
- Perform data preprocessing using Pandas and NumPy.
- Analyse retail sales patterns.
- Create meaningful visualizations using Matplotlib and Seaborn.
- Extract insights from transactional data.

## Dataset

**Source:** [UCI Machine Learning Repository – Online Retail](https://archive.ics.uci.edu/dataset/352/online+retail)

- Original records: 541,909
- Original columns: 8
- Dataset type: Retail transaction data
- Period: December 2010 – December 2011

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab
- Jupyter Notebook

## Project Methodology

### 1. Data Loading and Inspection
Loaded the retail dataset and examined its structure, columns, data types and statistical summaries.

### 2. Data Cleaning
- Identified missing values.
- Handled missing product descriptions.
- Preserved missing customer identifiers for analyses that do not require customer-level information.
- Detected and removed duplicate records.
- Converted columns into appropriate data types.

### 3. Invalid Transaction Handling
Identified cancelled invoices, negative quantities and zero or negative prices. Created a separate sales dataset containing valid positive-quantity transactions with positive prices.

### 4. Outlier Detection
Applied the Interquartile Range (IQR) method to identify unusual values in quantity and unit price. Used boxplots for visualization and investigation.

### 5. Data Visualization
Created visualizations to analyse:
- Monthly revenue trends.
- Top products by revenue.
- Top countries by revenue.
- Distribution of transaction quantities.
- Revenue by day of the week.
- Correlation between numerical sales variables.

## Project Results

| Metric | Result |
|---|---:|
| Original records | 541,909 |
| Records after duplicate removal | 536,641 |
| Valid sales records | 524,878 |
| Total sales revenue | 10,642,110.80 |
| Unique customers | 4,338 |
| Unique products | 3,922 |
| Countries analysed | 38 |

**Highest revenue country:** United Kingdom

**Highest revenue description:** DOTCOM POSTAGE

Note: DOTCOM POSTAGE represents a postage-related charge rather than a physical product.

## Repository Contents

- `Data_Cleaning_and_Visualization.ipynb` – Python implementation and analysis.
- `Cleaned_Online_Retail_Data.csv` – Processed sales dataset.
- `visualizations/` – Generated charts and visualizations.
- `reports/` – Project documentation.

## Conclusion

This project demonstrates the practical application of data preprocessing, cleaning and visualization techniques on a real-world retail dataset. The analysis provides insights into sales performance, product revenue and geographical trends while developing practical experience with essential Python data science libraries.


Artificial Intelligence and Machine Learning Undergraduate

BMS Institute of Technology, Bengaluru
