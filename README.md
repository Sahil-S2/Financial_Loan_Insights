![finance-accounting-analyze](finance-accounting-analyze.jpg)

# Financial_Loan_Insights

## Table of Contents

- [Project Overview](#Project-Overview)
- [Objectives](#Objectives)
- [Project Description](#Project-Description)
- [Technologies Used](#Technologies-Used)
- [Data Source](#Data-Source)
- [Key Attributes](#Key-Attributes)
- [Key Queries](#Key-Queries)
- [Tools and Technologies Used](#Tools-and-Technologies-Used)
  
## Project Overview

This project provides an in-depth analysis of loan data to uncover insights into lending practices and borrower behavior. By examining key metrics such as total applications, funded amounts, and payment records, we categorize loans into good and bad categories and analyze average interest rates across different loan purposes.
Also assess debt-to-income (DTI) ratios on a monthly basis, investigate loan amounts issued by state, and evaluate the average annual income of applicants by home ownership status. Through this analysis, we aim to inform data-driven decision-making in the banking sector and contribute to discussions on responsible lending and financial well-being.

## Objectives

**Analyze Loan Applications:** To explore the total number of loan applications and the total funded amount to assess the lending landscape.

**Evaluate Financial Metrics:** To calculate average interest rates and debt-to-income (DTI) ratios, providing insights into borrower financial health.

**Categorize Loan Performance:** To distinguish between good and bad loans, analyzing the implications for lenders and borrowers.

**Examine Geographic Trends:** To investigate loan amounts issued by state and distribution across application types, identifying regional lending patterns.

**Inform Decision-Making:** To utilize findings to support data-driven decisions in the banking sector, fostering responsible lending practices.


## Project Description

This project analyzes a banking dataset to reveal insights into loan trends, borrower behavior, and financial health. Using SQL queries, we explore loan applications, interest rates, repayment patterns, and state-based loan distributions. By uncovering patterns in loan issuance, defaults, and borrower financials, this project aims to support data-driven lending decisions and risk assessment strategies.

## Technologies Used

- SQL Server
- Git
- GitHub
- Markdown

## 📊 Data Source

The dataset used in this project is sourced from the Consumer Financial Protection Bureau (CFPB), which provides insights into mortgage lending data.

You can access the dataset here: [Summary of 2021 Data on Mortgage Lending](https://www.consumerfinance.gov/data-research/hmda/summary-of-2021-data-on-mortgage-lending/)


### 📋 Key Attributes

| Attribute               | Description                                                   |
|-------------------------|---------------------------------------------------------------|
| **id**                  | Unique identifier for each loan application                   |
| **address_state**       | State of the applicant's residence                            |
| **application_type**    | Type of loan application (e.g., individual, joint)            |
| **emp_length**          | Length of employment in years                                 |
| **emp_title**           | Job title of the applicant                                    |
| **grade**               | Assigned loan grade based on creditworthiness                 |
| **home_ownership**      | Type of home ownership (e.g., mortgage, rent)                 |
| **issue_date**          | Date when the loan was issued                                 |
| **last_credit_pull_date** | Date of the last credit report pull                        |
| **last_payment_date**   | Date of the last payment made                                 |
| **loan_status**         | Current status of the loan (e.g., fully paid, charged off)    |
| **next_payment_date**   | Date of the next scheduled payment                            |
| **member_id**           | Unique identifier for the loan member                         |
| **purpose**             | Purpose of the loan (e.g., credit card, debt consolidation)   |
| **sub_grade**           | Sub-category of the loan grade                                |
| **term**                | Length of the loan in months                                  |
| **verification_status** | Status of income verification (e.g., verified, not verified)  |
| **annual_income**       | Annual income of the applicant                                |
| **dti**                 | Debt-to-income ratio                                          |
| **installment**         | Monthly payment amount                                        |
| **int_rate**            | Interest rate of the loan                                     |
| **loan_amount**         | Total amount of the loan                                      |
| **total_acc**           | Total number of credit accounts                               |
| **total_payment**       | Total payments made on the loan                               |


## Key Queries

**Comprehensive Loan Analysis:**
This project explores various aspects of loan applications, including the total number of applications received, the total funded amount, and a detailed examination of payment records across different loan statuses.

**Interest and Financial Metrics:**
Analyze the average interest rates associated with different loan purposes and assess the average debt-to-income (DTI) ratios, segmented by month for the year 2021, to understand financial health among borrowers.

**Loan Performance Insights:**
The project categorizes loans into good and bad loans, calculating the total amount recorded in good loan applications and the percentage of bad loan applications to evaluate overall loan performance.

**State and Application Analysis:**
Investigate the total loan amount issued per state, along with the distribution of loans across various application types, to identify trends in lending behavior across regions.

**Statistical Overview:**
This analysis includes calculating the average annual income of applicants based on their home ownership status and determining the weighted average interest rate for each loan grade, providing a comprehensive view of the lending landscape.

## Tools and Technologies Used:

**SQL Server:** A powerful relational database management system used for storing, managing, and querying the banking dataset, enabling efficient data handling and analysis.

**SQL Queries:** Leveraged for crafting complex data retrieval and aggregation operations, including the use of Common Table Expressions (CTEs) and window functions to extract meaningful insights from the data.

**Data Visualization Tools:** Integration with tools like Tableau or Power BI for creating visually compelling dashboards and graphs to present the analysis results and trends effectively.

**Git:** A robust version control system that allows for tracking changes, managing project versions, and facilitating collaboration among team members.

**GitHub:** The chosen platform for hosting the project repository, providing a space for sharing code, documentation, and collaborative development with other contributors.


