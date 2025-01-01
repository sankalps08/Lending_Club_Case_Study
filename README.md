# Loan Default Risk Analysis 📊
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)

> An in-depth Exploratory Data Analysis (EDA) project focused on identifying and analyzing risk factors associated with loan defaults in consumer finance.

## Table of Contents
- [Project Overview](#project-overview)
- [Business Understanding](#business-understanding)
- [Dataset Description](#dataset-description)
- [Analysis Approach](#analysis-approach)
- [Key Findings](#key-findings)
- [Technologies Used](#technologies-used)
- [Conclusions](#conclusions)
- [Contact](#contact)

## Project Overview
The Loan Default Risk Analysis project aims to leverage Exploratory Data Analysis (EDA) to understand the underlying factors contributing to loan defaults among consumers. By analyzing historical loan applicant data, this project helps financial institutions mitigate risks associated with lending, ultimately guiding decision-making processes to improve profitability while ensuring responsible lending.

Understanding the tendencies and attributes that lead to loan defaults enables companies to refine their lending criteria, lower credit losses, and extend better service to creditworthy applicants.

## Business Understanding
lending companies face crucial decisions when approving loan applications. This project tackles two primary risks:
- **Type I Error**: Revenue loss from rejecting creditworthy applicants
- **Type II Error**: Financial loss from approving high-risk applicants

The analysis focuses on identifying patterns and indicators that suggest a higher likelihood of loan default, enabling better risk assessment and decision-making.

## Dataset Description
- **Time Period**: 2007-2011
- **Scope**: Complete loan data including:
  - Loan application details
  - Borrower information
  - Loan status (Fully paid, Current, Charged-off)
  - Various financial metrics

## Analysis Approach
1. **Data Preprocessing**
   - Data cleaning and validation
   - Feature engineering
   - Missing value treatment

2. **Exploratory Analysis**
   - Univariate analysis
   - Bivariate analysis
   - Segment analysis
   - Correlation studies
   - Multivariate analysis

3. **Risk Factor Analysis**
   - Credit grade assessment
   - Debt-to-Income ratio impact
   - Geographic distribution
   - Loan term analysis

## Key Findings

### Credit Profile Analysis
- Higher default rates in Credit Grades B, C, and D
- Strong correlation between high DTI ratios (>43%) and defaults
- Credit history length significantly impacts default probability

### Demographic Insights
- Rental status shows highest default rates
- Regional variations in default patterns
- Seasonal trends with Q4 showing peak defaults

### Loan Characteristics
- Larger loans (>15K) show increased default risk
- 36-month terms perform better than 60-month terms
- Debt consolidation loans show highest default rates

## Technologies Used
- Python 3.12.3
- Pandas for data manipulation(2.2.3)
- NumPy for numerical operations(2.1.3)
- Matplotlib(3.10.0)/Seaborn(0.13.2) for visualization
- Jupyter Notebook for analysis

## Conclusions

### Risk Mitigation Strategies
1. Implement stricter credit assessment for grades B, C, and D
2. Set DTI ratio limits at 36%
3. Adjust loan terms based on regional risk factors
4. Enhanced scrutiny for high-value loans

### Portfolio Optimization
1. Promote shorter loan terms (36 months)
2. Focus on higher-income borrowers
3. Implement seasonal risk adjustments
4. Strengthen verification processes

## Contact
Created by [@Sankalps08] - feel free to contact me!

---
*Note: This project was completed as part of an advanced data analysis study focusing on risk analytics in banking.*

