## Loan Performance and Investor Return Analysis (Tchnocolabs Softwares Internship)

This repository is dedicated to analyzing loan performance, borrower characteristics, and investor returns within the Peer-to-Peer (P2P) lending market. The project combines advanced data processing techniques, exploratory analysis, and interactive visualizations to uncover insights for improving loan portfolio performance.

---

## Project Overview

P2P lending platforms enable direct transactions between borrowers and lenders, bypassing traditional financial institutions. This project evaluates:
- Loan performance across various borrower profiles.
- Factors influencing investor returns.
- Risk assessment strategies to minimize defaults and optimize yields.

---

## Key Features

1. **Data Preprocessing and Cleaning**
   - Transformation of key date-related columns to a standardized format.
   - Handling missing values through mode and median imputation.
   - Outlier detection using the IQR method for financial variables like APR and credit scores.

2. **Data Encoding**
   - Binary encoding of `LoanStatus` for better analysis of default trends.
   - Addition of derived metrics like `Default Rate` for portfolio health assessment.

3. **Exploratory Data Analysis**
   - Visualization of borrower characteristics such as credit grades and Prosper ratings.
   - Analysis of trends in delinquency rates, default risks, and lender yields.

4. **Dashboard Insights**
   - Interactive dashboards in Power BI provide a dynamic view of:
     - Loan distribution across statuses.
     - Trends in borrower risk and investor returns.
     - Performance across credit grades and loan terms.

---

## Dataset

### Prosper Loan Dataset
The dataset contains 113,937 rows and 81 columns, with key features such as:
- **LoanStatus**: Current, Defaulted, Completed, etc.
- **BorrowerAPR**: Ranging from 0% to ~29%.
- **LoanOriginalAmount**: Minimum $1,000 to maximum $25,000.
- **CreditGrade**: Borrower’s creditworthiness (e.g., AA, B, HR).

The dataset includes borrower demographics, loan statuses, credit profiles, and investor details.

---

## Objectives

1. **Assess Loan Performance**
   - Analyze the proportion of defaulted, current, and delinquent loans.
   - Identify borrower attributes that correlate with successful repayments.

2. **Evaluate Investor Returns**
   - Explore relationships between borrower characteristics and investor yields.

3. **Optimize Risk Management**
   - Track delinquency rates and develop strategies to reduce defaults.

4. **Interactive Dashboards**
   - Create Power BI dashboards to visualize trends and provide actionable insights.

---

## Tools and Technologies

1. **Programming and Data Analysis**
   - Python: Data processing and analysis.
   - Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`.

2. **Data Visualization**
   - Power BI: Interactive dashboards for loan portfolio analysis.


---

