# Loan Analysis Project

## 🎯 Project Goal

This project employs **Exploratory Data Analysis (EDA)** on a historical loan portfolio dataset to identify the **driving factors (driver variables)** behind customer loan default.

The main business objective is to help a **consumer finance company** minimise financial loss (called **credit loss**) by proactively identifying and mitigating risk associated with 'risky' loan applicants.

## 💡 Business Problem

A finance company faces two primary types of risk when evaluating loan applications:
1.  **Loss of Business:** Occurs if a loan is rejected, but the applicant would have been likely to repay.
2.  **Financial Loss (Credit Loss):** Occurs if a loan is approved, but the applicant is not likely to repay (i.e., they default).

By understanding the key attributes of defaulters, the company can implement proactive measures such as **denying the loan**, **reducing the loan amount**, or **lending at a higher interest rate** to high-risk applicants, thereby cutting down credit loss.

## 📊 Data Overview & Target Variable

The analysis focuses on how **consumer attributes** and **loan attributes** influence the tendency of default.

* **Dataset:** Complete loan data for all loans issued through a past time period (2007 to 2011).
* **Target Variable:** The `loan_status` column. The customers labelled as **'Charged-off'** are the defaulters and the largest source of loss. Applicants with **'Fully Paid'** status are the successful cases.

## 🛠️ Analysis Approach

The approach uses standard EDA methodology to understand the problem:
1.  **Data Understanding:** Researching the domain and significance of variables (Risk Analytics).
2.  **Univariate Analysis:** Studying distributions of variables in isolation.
3.  **Bivariate Analysis:** Examining the relationship between predictor variables and the target variable (`loan_status`) to find strong indicators of default.
4.  **Presentation:** Explaining results in business terms and summarising the most important results with visualisations.

Thank You
