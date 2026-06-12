# Cohort Retention & Customer Lifetime Value (CLTV) Analysis

## Project Overview

This project was developed as part of a Data Analytics Internship Program. The objective is to analyze customer retention behavior and calculate Customer Lifetime Value (CLTV) using transactional retail data.

## Business Problem

Acquiring new customers is more expensive than retaining existing customers. Businesses need to understand customer retention patterns, identify churn, and estimate the lifetime value of customers.

This project uses Cohort Analysis and CLTV calculations to provide actionable business insights.

## Dataset

Dataset: Online Retail Dataset

The dataset contains:
- Customer transactions
- Invoice information
- Purchase dates
- Product details
- Quantity purchased
- Unit prices

## Project Objectives

### Data Cleaning
- Handle missing Customer IDs
- Remove cancelled transactions
- Convert dates into datetime format
- Create Sales metrics

### Cohort Analysis
- Create Invoice Month
- Create Cohort Month
- Calculate Cohort Index
- Build Retention Matrix
- Calculate Retention Rates
- Generate Retention Heatmap

### Customer Lifetime Value Analysis
- Calculate Average Order Value (AOV)
- Calculate Purchase Frequency
- Calculate Customer Lifetime Value (CLTV)
- Identify Top Revenue Customers

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Git
- GitHub
- VS Code

## Project Structure

cohort-retention-cltv-analysis

├── data

├── notebooks

│   ├── 01_data_cleaning.ipynb

│   └── 02_cltv_analysis.ipynb

├── outputs

├── README.md

└── PROJECT_SUMMARY.md

## Key Analysis Performed

### Data Cleaning
- Removed records with missing Customer IDs
- Removed cancelled transactions
- Created Sales column

### Cohort Analysis
- Calculated customer acquisition month
- Created retention cohorts
- Built retention matrix
- Generated retention heatmap

### CLTV Analysis
- Customer revenue calculation
- Average Order Value (AOV)
- Purchase Frequency
- Customer Lifetime Value (CLTV)
- Top Customer Revenue Analysis

## Key Findings

### Cohort Retention Insights

- Customer retention decreases over time.
- The highest customer drop-off occurs after the first month.
- Customers retained beyond Month 2 show stronger long-term engagement.

### CLTV Insights

- A small percentage of customers contribute a large percentage of total revenue.
- Increasing customer retention directly improves CLTV.
- Loyal customers generate significantly higher business value.

## Business Recommendations

1. Improve customer onboarding experience.
2. Launch retention campaigns after the first purchase.
3. Create loyalty and rewards programs.
4. Re-engage inactive customers through targeted marketing.
5. Focus acquisition efforts on high-value customer segments.

## Outcome

Successfully developed a complete customer retention and Customer Lifetime Value analytics workflow using Python and data visualization techniques. The project provides actionable business insights that can support customer retention strategies and revenue growth initiatives.

## Author

Jyoti Damji

Data Analytics Internship Project
