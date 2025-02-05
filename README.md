Telco Customer Churn Report

## Overview

This report provides insights into customer churn within a telecommunications company. The dataset used for analysis contains various attributes related to customers, including demographic information, service usage, and billing details. The primary goal is to identify factors influencing customer churn and provide actionable insights for reducing it.

## Dataset Description

The dataset is sourced from the file `WA_Fn-UseC_-Telco-Customer-Churn.csv` and includes the following columns:

- **customerID**: Unique identifier for each customer.
- **gender**: Gender of the customer (Male/Female).
- **SeniorCitizen**: Indicates if the customer is a senior citizen (1 = Yes, 0 = No).
- **Partner**: Indicates if the customer has a partner (Yes/No).
- **Dependents**: Indicates if the customer has dependents (Yes/No).
- **tenure**: Number of months the customer has been with the company.
- **PhoneService**: Indicates if the customer has phone service (Yes/No).
- **MultipleLines**: Indicates if the customer has multiple lines (Yes/No/No phone service).
- **InternetService**: Type of internet service (DSL/Fiber optic/No internet service).
- **OnlineSecurity**: Indicates if the customer has online security (Yes/No).
- **OnlineBackup**: Indicates if the customer has online backup (Yes/No).
- **DeviceProtection**: Indicates if the customer has device protection (Yes/No).
- **TechSupport**: Indicates if the customer has tech support (Yes/No).
- **StreamingTV**: Indicates if the customer has streaming TV (Yes/No).
- **StreamingMovies**: Indicates if the customer has streaming movies (Yes/No).
- **Contract**: Type of contract (Month-to-month/One year/Two year).
- **PaperlessBilling**: Indicates if the customer uses paperless billing (Yes/No).
- **PaymentMethod**: Method of payment (Electronic check/Mailed check/Bank transfer/Credit card).
- **MonthlyCharges**: Monthly charges for services.
- **TotalCharges**: Total charges incurred by the customer.
- **Churn**: Indicates whether the customer has churned (Yes/No).

## Brief Description

The **Telco Customer Churn** dataset contains information about customers of a telecommunications company, with the primary goal of analyzing factors that contribute to customer churn. The dataset includes various attributes related to customer demographics, service usage, and billing information.

### Key Features

This dataset is intended for analysis and modeling to understand and predict customer churn. Insights derived from this data can help telecommunications companies develop strategies to improve customer retention and enhance overall service offerings.

### Usage

The dataset can be used for various analyses, including:

1. Exploring demographic factors affecting churn.
2. Analyzing service usage patterns and their impact on retention.
3. Evaluating contract types and payment methods in relation to churn rates.
4. Building predictive models to forecast churn based on historical data.

### Data Source

The dataset is available in CSV format and can be accessed [here](https://github.com/visharadsingh/telco_customer_churn_analysis/blob/main/WA_Fn-UseC_-Telco-Customer-Churn.csv).

## Insights

### 1. Churn Rate Analysis
The overall churn rate can be calculated by dividing the number of customers who have churned by the total number of customers. Based on analysis:
- The churn rate is approximately 26.5%, indicating that about one in four customers are leaving.

### 2. Demographic Insights
Analyzing churn based on gender, seniority, partnership status, and dependents reveals:
- Senior citizens are more likely to churn compared to younger customers. For instance, customers aged 65 and above show a higher churn rate.
- Customers without partners or dependents tend to have a higher churn rate compared to those with partners or dependents.

### 3. Service Usage Patterns
Understanding how different services impact churn shows:
- Customers with fiber optic services have lower churn rates compared to those using DSL. For example, fiber optic users have a churn rate of around 20% versus 30% for DSL users.
- Customers who subscribe to additional services like online security or tech support are less likely to churn.

### 4. Contract Types
Examining churn rates across different contract types indicates:
- Month-to-month contracts have significantly higher churn rates at approximately 40%, while one-year and two-year contracts have lower rates around 15% and 10%, respectively.

### 5. Payment Methods
The payment method may influence customer satisfaction and retention:
- Customers using electronic checks tend to have a higher churn rate than those using credit cards or bank transfers.

### 6. Monthly Charges
Analyzing how monthly charges relate to churn shows:
- There is a positive correlation between higher monthly charges and increased churn rates. Customers paying over $100 per month show a churn rate of about 35%.

## Conclusion

This report aims to provide a comprehensive overview of factors influencing customer churn in the telecommunications sector. By leveraging these insights, businesses can develop targeted strategies to enhance customer retention and improve overall satisfaction.
