
# Paisabazaar Banking Fraud Analysis - Credit Score Classification

## Project Overview

The **Paisabazaar Banking Fraud Analysis** project is a comprehensive exploratory data analysis (EDA) and credit assessment initiative designed to analyze customer financial behavior and classify individuals based on their creditworthiness. This capstone project aims to help Paisabazaar, a leading financial services platform, make smarter lending decisions by accurately predicting customer credit scores and reducing the likelihood of loan defaults.

The project leverages a dataset of banking customers with detailed financial and demographic information to identify key factors influencing credit risk and develop actionable insights for improved credit evaluation.

---

## Problem Statement

**Challenge**: Paisabazaar faces challenges in accurately assessing customer creditworthiness using traditional credit scoring methods, which often fail to capture the full range of financial behaviors and personal characteristics. This can lead to:
- Inaccurate risk assessments
- Suboptimal lending decisions
- Increased loan default rates

**Objective**: Build a data-driven credit scoring solution that classifies customers into three distinct credit score categories:
- **Good**: Low-risk customers suitable for favorable loan terms
- **Standard**: Moderate-risk customers requiring standard evaluation
- **Poor**: High-risk customers requiring additional scrutiny or alternative products

---

## Key Business Objectives

1. **Enhance Risk Management**
   - Accurately evaluate creditworthiness to reduce loan defaults
   - Support safer lending decisions for partner institutions

2. **Streamline Loan Approvals**
   - Automate customer classification into credit score categories
   - Accelerate the loan approval process with consistent evaluation criteria

3. **Deliver Personalized Financial Solutions**
   - Offer tailored financial product recommendations based on credit profiles
   - Improve customer satisfaction through targeted product matching
   - Increase business growth through data-informed decision-making

---

## Dataset Description

The dataset contains **100,000 banking customer records** with the following key attributes:

### Demographic Information
- `ID`: Unique identifier for each record
- `Customer_ID`: Unique identifier for each customer
- `Name`: Customer name
- `Age`: Customer age
- `SSN`: Social Security Number
- `Occupation`: Customer occupation
- `Month`: Time period of the data

### Income & Financial Information
- `Annual_Income`: Total annual income
- `Monthly_Inhand_Salary`: Monthly take-home salary
- `Total_EMI_per_month`: Total monthly EMI payments
- `Amount_invested_monthly`: Monthly investment amount
- `Monthly_Balance`: Monthly balance in accounts

### Banking & Credit Information
- `Num_Bank_Accounts`: Number of bank accounts held
- `Num_Credit_Card`: Number of credit cards held
- `Interest_Rate`: Average interest rate on loans
- `Num_of_Loan`: Total number of loans
- `Type_of_Loan`: Classification of loan types
- `Outstanding_Debt`: Total outstanding debt amount

### Payment & Credit Behavior
- `Delay_from_due_date`: Days delayed in payment
- `Num_of_Delayed_Payment`: Total number of delayed payments
- `Payment_of_Min_Amount`: Minimum payment compliance status
- `Payment_Behaviour`: Overall payment behavior pattern
- `Changed_Credit_Limit`: Credit limit modifications
- `Num_Credit_Inquiries`: Number of credit inquiries

### Credit Metrics
- `Credit_Utilization_Ratio`: Percentage of available credit used
- `Credit_History_Age`: Length of credit history
- `Credit_Mix`: Diversity of credit types
- `Credit_Score`: Target variable (Good/Standard/Poor)

---

## Analysis Framework

### 1. Data Wrangling & Preprocessing
- Handle missing values and data inconsistencies
- Encode categorical variables
- Normalize and scale numerical features
- Remove or treat outliers appropriately

### 2. Exploratory Data Analysis (EDA)

#### **Univariate Analysis**
- Distribution analysis of individual variables
- Identification of age groups and customer segments
- Credit score distribution visualization
- Income and debt variation assessment
- Detection of extreme values and outliers

#### **Bivariate Analysis**
- Income vs. Outstanding Debt relationships
- Credit Utilization Ratio vs. Credit Score correlation
- Monthly Salary vs. Delayed Payments patterns
- Feature pair relationships affecting creditworthiness

#### **Multivariate Analysis**
- Correlation heatmaps of financial variables
- Multi-dimensional customer segmentation
- Combined effect of multiple features on credit risk
- Clustering and pattern identification

### 3. Feature Engineering
- Creation of derived financial metrics
- Feature interactions and combinations
- Risk indicator development
- Dimensionality reduction where applicable

### 4. Data Visualization
- Distribution plots and histograms
- Box plots for outlier detection
- Scatter plots for relationships
- Heatmaps for correlations
- Pie charts for categorical distributions
- Line charts for trend analysis
- Pair plots for multi-dimensional relationships

### 5. Insights & Recommendations
- Identification of key credit risk factors
- Customer segmentation strategies
- Actionable insights for lending decisions
- Business recommendations based on findings

---

## Project Structure

```
Paisabazaar_Banking_Fraud_Analysis/
├── Capstone_Paisabazaar_Banking_Fraud_Analysis.ipynb  # Main analysis notebook
├── dataset.csv                                         # Customer dataset
└── README.md                                           # Project documentation
```

---

## Technologies & Libraries Used

- **Python 3.x**
- **Pandas**: Data manipulation and cleaning
- **NumPy**: Numerical computations
- **Matplotlib**: Data visualization
- **Seaborn**: Statistical visualization
- **Scikit-learn**: (For potential preprocessing and analysis)

---

## Key Findings (Expected Outcomes)

The analysis is expected to reveal:

1. **Primary Risk Indicators**: Top financial factors influencing credit scores
2. **Customer Segments**: Distinct customer profiles based on financial behavior
3. **Payment Behavior Patterns**: How payment history correlates with creditworthiness
4. **Income-Debt Relationships**: The impact of income levels on credit risk
5. **Credit Utilization Impact**: How credit usage affects credit scores

---

## Project Execution Checklist

-  Data Loading & Exploration
-  Data Cleaning & Preprocessing
-  Univariate Analysis
-  Bivariate Analysis
-  Multivariate Analysis
-  Feature Engineering
-  Visualization & Interpretation
-  Actionable Recommendations

---

## How to Use This Project

1. **Install Dependencies**:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn jupyter
   ```

2. **Open the Notebook**:
   ```bash
   jupyter notebook Capstone_Paisabazaar_Banking_Fraud_Analysis.ipynb
   ```

3. **Run the Analysis**: Execute cells sequentially to reproduce the entire analysis pipeline

4. **Review Outputs**: Examine visualizations and insights generated throughout the notebook

---

## Expected Deliverables

- Comprehensive EDA report with visualizations
- Statistical summary of key variables
- Correlation analysis and insights
- Customer segmentation analysis
- Business recommendations for credit assessment
- Well-documented, production-grade code

---

## Project Information

- **Project Type**: Exploratory Data Analysis (EDA) & Credit Assessment
- **Contribution**: Individual
- **Member**: Himanshu Shende

---

## Code Quality Standards

This project adheres to:
- Well-structured, formatted, and commented code
- Clear variable naming conventions
- Comprehensive documentation
- Exception handling for robustness
- Production-grade, deployment-ready code
- Each logic block includes detailed comments

---

## Learning Outcomes

Upon completing this project, stakeholders will understand:
- How to perform comprehensive exploratory data analysis
- Key financial indicators affecting creditworthiness
- How to identify patterns and anomalies in customer data
- Customer segmentation strategies
- Data-driven decision-making for financial services
- Best practices in data analysis and visualization

---

## Notes

- This project demonstrates end-to-end EDA capabilities
- The notebook is designed to be fully executable in one run without errors
- All visualizations include proper labels, legends, and interpretations
- Results can be directly applied to improve Paisabazaar's credit assessment processes

---

*Last Updated: January 2026*

## Installation

To run this project, you need to have Python and the required libraries installed. You can install the necessary libraries using pip:

```bash
pip install pandas numpy matplotlib seaborn
