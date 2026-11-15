# Telco Customer Churn Analysis

## Project Overview

This project explores customer churn patterns within a telecommunications company using Microsoft Excel 2019. The analysis focuses on identifying customer characteristics and service patterns associated with higher churn rates and translating those findings into actionable business recommendations.

The goal was to move beyond overall churn figures and investigate specific customer segments to uncover patterns that could help inform customer retention strategies.

## Business Objective

Identify customer segments associated with higher churn and investigate potential factors contributing to customer attrition, including:

- Contract type
- Customer tenure
- Internet service
- Technical support availability
- Payment methods

## Tools & Skills

- **Microsoft Excel 2019**
- Data cleaning and preparation
- Data quality checks and validation
- PivotTables and calculated churn rates
- Customer segmentation
- Dashboard development
- Data visualization
- Business analysis and recommendations

## Project Workflow

### 1. Data Cleaning & Preparation

- Reviewed the original dataset and created a separate working copy.
- Checked customer IDs for missing values and duplicates.
- Investigated blank `TotalCharges` entries.
- Converted 11 single-space `TotalCharges` values to numeric zero in a cleaned helper column. These records had zero tenure and no recorded churn.
- Preserved the original source data for reference.

### 2. Exploratory Data Analysis

Used Excel PivotTables to examine churn across customer segments, including contract types, tenure groups, internet services, technical support availability, and payment methods.

Calculated churn rates within relevant customer groups to make comparisons more meaningful than raw customer counts alone.

### 3. Dashboard & Findings

Developed an Excel dashboard to communicate key metrics and visual patterns. A separate findings summary presents the major observations and recommendations.

## Key Findings

- **Contract Type:** Month-to-month customers had the highest churn rate at 42.71%, compared with 11.27% for one-year contracts and 2.83% for two-year contracts.
- **Customer Tenure:** Customers within their first 12 months had a churn rate of 48.28%. Churn generally declined as customer tenure increased.
- **Internet Service:** Fiber optic customers had a churn rate of 41.89%, compared with 18.96% for DSL customers.
- **Technical Support:** Within the fiber optic, month-to-month segment, customers without technical support had a churn rate of 57.52%, compared with 38.86% among customers with support.
- **Payment Method:** Within the fiber optic, month-to-month segment, electronic check customers had the highest churn rate at 60.37%.

These findings identify associations within the dataset and do not establish that any single factor caused customers to leave.

## Business Recommendations

Based on the analysis, the company should consider:

1. Investigating contract benefits, pricing, and promotional offers to better understand the high churn among month-to-month customers.
2. Reviewing the first-year customer experience and identifying opportunities to improve early retention.
3. Evaluating technical support performance, including response times, resolution rates, and customer satisfaction.
4. Investigating the electronic-check payment experience to identify potential friction points.
5. Continuing targeted customer segmentation to better understand which groups may benefit from retention initiatives.

## Project Deliverables

- Excel workbook containing the cleaned data, data quality checks, PivotTable analysis, dashboard, and findings.
- Dashboard screenshots.
- Findings and business recommendations.

## Dataset

IBM Telco Customer Churn dataset (`WA_Fn-UseC_-Telco-Customer-Churn.csv`).

The dataset contains 7,043 customer records and includes customer demographics, account information, subscribed services, payment methods, and churn status.

## Project Takeaway

This project strengthened my ability to work through an end-to-end data analysis workflow in Excel, from data preparation and validation to exploratory analysis, visualization, and business recommendations.

It reinforced the importance of investigating customer segments rather than relying solely on overall metrics when evaluating business performance.
