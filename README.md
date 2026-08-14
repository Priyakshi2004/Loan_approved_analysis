# Loan Approval Analysis Dashboard

An end-to-end data analysis project focused on understanding loan approval patterns and identifying the key factors associated with loan approval.

## Project Objective

The objective of this project is to analyze loan applications and build an interactive Power BI dashboard that provides insights into:

- Overall loan approval and rejection rates
- Relationship between CIBIL score and loan approval
- Impact of Loan-to-Income (LTI) ratio on approval
- Loan amount vs applicant income
- Approval patterns across employment status
- Key characteristics of approved and rejected applications

## Tools & Technologies

- **Python** — Data cleaning and exploratory data analysis
- **Pandas** — Data manipulation and analysis
- **Power BI** — Interactive dashboard and data visualization
- **Jupyter Notebook / Google Colab** — Python analysis

## Dashboard

The dashboard provides an overview of loan applications along with interactive filters for:

- Loan Status
- CIBIL Band
- Education

### Key KPIs

- **Total Applications:** 4,269
- **Approved Loans:** 2,656
- **Rejected Loans:** 1,613
- **Approval Rate:** 62.7%
- **Average CIBIL Score:** ~600

## 🔍 Key Insights

### CIBIL Score
Applicants with CIBIL scores below 600 have a significantly lower approval rate compared with applicants in higher CIBIL bands.

### Loan-to-Income Ratio
Approval rates vary across different Loan-to-Income bands, providing insight into how the relationship between income and requested loan amount affects approval decisions.

### Income vs Loan Amount
The scatter plot shows the relationship between applicant income and requested loan amount, separated by loan approval status.

### Employment Status
Approval rates are relatively similar between self-employed and non-self-employed applicants in this dataset.


