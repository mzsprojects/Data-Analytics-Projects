# Project Background
This project was completed as part of my Google Advanced Data Analytics Professional Certificate on Coursera. It involves analyzing NYC Yellow Taxi trip data through Exploratory Data Analysis (EDA), applying Hypothesis Testing, and building a Linear Regression model to uncover insights about customer payments and trip fares.

## Overview 
**Business Context:** Taxi operators and city transport services need to understand trip patterns, payment preferences, and fare structures to optimize their business strategy. This project applies statistical and machine learning techniques to discover such insights.  
**Dataset:** 22,699 records from NYC Yellow Taxi 2017 trip data.  
**Key Variables:** Pickup & drop-off times, distance, fare, tips, payment method, passenger counts, and trip totals.  
**Goal:** Extract insights from trip-level data, evaluate the impact of payment methods on fares, and build a predictive model for decision-making.

# Analysis Components
### 1. Data Validation & Cleaning
- Confirmed dataset size: 22,699 records, no NULL values, no duplicates.
- Identified and corrected data type mismatches (e.g., datetime stored as object).
- Flagged and reviewed unusual values (e.g., RatecodeID = 99).
- Noted extreme outliers such as trips with 34 miles distance or $1200 fare totals.

### 2. Exploratory Data Analysis (EDA)
- Summarized data distribution across fares, tips, and trip distances.
- Examined categorical variables (payment_type, VendorID, RatecodeID).
- Visualized outliers and anomalies.
- Established a clean dataset foundation for further testing and modeling.

### 3. Hypothesis Testing
- Tested whether payment method impacts fare amount (credit card vs. cash).
- Null Hypothesis ($H_0$): No difference in mean fare amount.
- Alternative Hypothesis ($H_A$): Significant difference in mean fare amount.
- **Result:** P-value < 0.05 → Reject $H_0$. Customers paying by credit card spend more on average than those paying cash.
- **Key Insight:** Promoting credit card usage could increase overall revenue.

### 4. Regression Analysis
- Built and evaluated a Linear Regression model to predict trip fares.
- Analyzed residuals and model assumptions.
- Identified features with predictive power (e.g., distance, trip duration, tips).
- Quantified relationships between trip characteristics and total fare amount.

# Key Findings
- Data quality is strong (no missing/duplicate values) but includes outliers requiring attention.
- Payment method significantly affects fare amounts: credit card users tend to pay more.
- Linear regression provides predictive insights into fare values, supporting data-driven decision-making for taxi operators.

# Recommendations
- Revenue Strategy: Encourage credit card payments to maximize average fare per customer.
- Data Monitoring: Implement regular checks for anomalous values (e.g., abnormally high fares/distances).
- Predictive Analytics: Use regression models to forecast fares and optimize pricing strategies.

# Technical Skills Demonstrated
- Data Cleaning: Outlier handling, datatype corrections, categorical processing.
- Exploratory Data Analysis: Trend identification, categorical and numerical summaries.
- Hypothesis Testing: Formal statistical testing and interpretation.
- Regression Modeling: Linear regression, residual analysis, model validation.
- Visualization: Data-driven storytelling with plots and distributions.

# Tools & Libraries
- Python: Pandas, NumPy, Matplotlib, Seaborn
- Statsmodels, SciPy, Scikit-learn
- Jupyter Notebook

---

Google Advanced Data Analytics Professional Certificate Project  
Completed: June 2025
