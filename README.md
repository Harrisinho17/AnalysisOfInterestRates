# Risk Management Dashboard for Loan Portfolios

## Project Overview
This project focuses on analyzing a bank's loan portfolio to assess risk levels and predict potential loan defaults. By leveraging SQL for data extraction, R for risk analysis and predictive modeling, and Tableau for creating an interactive dashboard, the project aims to provide insights into the overall health of the loan portfolio and help identify high-risk segments.

## Table of Contents
1. [Tools and Technologies](#tools-and-technologies)
2. [Sample Data Sources](#sample-data-sources)
3. [Installation and Setup](#installation-and-setup)
4. [Project Workflow](#project-workflow)
5. [Key Features](#key-features)
6. [Next Steps](#next-steps)

---

## Tools and Technologies
To successfully complete this project, the following tools and technologies will be used:

### 1. **SQL** 
   - **Purpose:** Data extraction, filtering, and cleaning.
   - **Required Tools:** PostgreSQL, MySQL, or any SQL-based database.
   - **Installation:** 
     - PostgreSQL: [Download PostgreSQL](https://www.postgresql.org/download/)
     - MySQL: [Download MySQL](https://dev.mysql.com/downloads/mysql/)

### 2. **R**
   - **Purpose:** Data analysis, risk modeling, and predictive analytics (e.g., logistic regression for default prediction).
   - **Required Tools:** R programming language and RStudio IDE.
   - **Installation:** 
     - R: [Download R](https://cran.r-project.org/)
     - RStudio: [Download RStudio](https://rstudio.com/products/rstudio/download/)

### 3. **Tableau**
   - **Purpose:** Visualization of loan portfolio health, risk indicators, and predictive results.
   - **Required Tools:** Tableau Desktop or Tableau Public.
   - **Installation:** 
     - Tableau Public (Free): [Download Tableau Public](https://public.tableau.com/en-us/s/download)
     - Tableau Desktop (Paid/Trial): [Download Tableau Desktop](https://www.tableau.com/products/desktop)

---

## Sample Data Sources
Here are a few publicly available datasets you can use for risk analysis in loan portfolios:

### 1. **Lending Club Loan Data**
   - **Description:** This dataset contains detailed loan information including loan amount, grade, interest rate, and borrower information. It is widely used for risk analysis.
   - **Source:** [Kaggle - Lending Club Loan Data](https://www.kaggle.com/wordsforthewise/lending-club)

### 2. **Fannie Mae Single-Family Loan Performance Data**
   - **Description:** This dataset provides performance data on a portfolio of single-family mortgage loans, including delinquency, credit score, and more.
   - **Source:** [Fannie Mae Loan Performance](https://datadynamics.fanniemae.com/dataset/single-family-loan-performance-data)

### 3. **World Bank - Global Financial Development Database**
   - **Description:** A comprehensive dataset on financial institutions' performance, including non-performing loans and other risk indicators.
   - **Source:** [World Bank Financial Data](https://databank.worldbank.org/source/global-financial-development)

### 4. **Credit Card Fraud Detection Dataset**
   - **Description:** While this dataset focuses on credit card fraud, you can adapt it to analyze patterns that may indicate loan risk.
   - **Source:** [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/mlg-ulb/creditcardfraud)

---

## Installation and Setup

### Step 1: Install Required Tools
- Install PostgreSQL/MySQL, R, RStudio, and Tableau as listed in the [Tools and Technologies](#tools-and-technologies) section.
- Make sure to set up the database and import the sample data.

### Step 2: Set Up Data Environment
- Load the selected dataset (e.g., Lending Club Loan Data) into your SQL database.
- Perform data cleaning and create views or tables as necessary for the analysis.

### Step 3: Install R Packages
- The following R packages are required:
  - `dplyr` for data manipulation
  - `ggplot2` for data visualization
  - `caret` for predictive modeling
  - `ROCR` for model evaluation

---

## Project Workflow

### 1. Data Extraction (SQL)
  - Extract loan and borrower information from the database.
  - Clean the data and filter by relevant columns such as loan amount, credit score, and loan status.

### 2. Risk Analysis & Modeling (R)
  - Analyze loan data to identify key risk factors.
  - Build predictive models to predict the likelihood of loan defaults.
  - Evaluate model performance using AUC, confusion matricies and other metrics.

### 3. Dashboard Creation (Tableau)
  - Create interactive visualizations to show:
      - Loan portfolio breakdown by risk level.
      - Performance metrics such as the percentage of high-risk loans.
      - Model predictions and their accuracy.
   
## Key Features 
  - Interactive Risk Dashboard: Display portfolio health and track key risk indicators.
  - Predictive Modeling: Assess the likelihood of loan defaults using logistic regression.
  - Data Exploration: Use SQL to query and explore the dataset, identifying risk factors.


