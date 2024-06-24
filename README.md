# Customer Churn Analysis Dashboard

## Overview
This project involves the creation of a comprehensive dashboard to analyze customer churn using Power BI. The dataset used includes various customer details and their interaction with the services provided. The goal is to identify patterns and factors contributing to customer churn and provide insights for business decisions to reduce churn rates.

## Dataset
The dataset used for this analysis is `Customer Churn-Dataset.xlsx`, which contains information about customers, including their demographics, account details, and usage metrics.

### Key Columns
- **CustomerID**: Unique identifier for each customer.
- **Gender**: Gender of the customer.
- **SeniorCitizen**: Indicates if the customer is a senior citizen (1) or not (0).
- **Partner**: Indicates if the customer has a partner (Yes/No).
- **Dependents**: Indicates if the customer has dependents (Yes/No).
- **Tenure**: Number of months the customer has stayed with the company.
- **PhoneService**: Indicates if the customer has phone service (Yes/No).
- **MultipleLines**: Indicates if the customer has multiple lines (Yes/No/No phone service).
- **InternetService**: Type of internet service the customer has (DSL/Fiber optic/No).
- **OnlineSecurity**: Indicates if the customer has online security (Yes/No/No internet service).
- **OnlineBackup**: Indicates if the customer has online backup (Yes/No/No internet service).
- **DeviceProtection**: Indicates if the customer has device protection (Yes/No/No internet service).
- **TechSupport**: Indicates if the customer has tech support (Yes/No/No internet service).
- **StreamingTV**: Indicates if the customer has streaming TV (Yes/No/No internet service).
- **StreamingMovies**: Indicates if the customer has streaming movies (Yes/No/No internet service).
- **Contract**: Type of contract the customer has (Month-to-month/One year/Two year).
- **PaperlessBilling**: Indicates if the customer uses paperless billing (Yes/No).
- **PaymentMethod**: Method of payment (Electronic check/Mailed check/Bank transfer (automatic)/Credit card (automatic)).
- **MonthlyCharges**: The amount charged to the customer monthly.
- **TotalCharges**: The total amount charged to the customer.
- **Churn**: Indicates if the customer churned (Yes/No).

## Dashboard Features
- **Overview**: Provides a high-level summary of the churn rate and key metrics.
- **Demographics**: Analyzes churn based on customer demographics like age, gender, and senior citizen status.
- **Services**: Examines how different services (phone, internet, etc.) impact churn.
- **Account Information**: Looks at account details such as tenure, contract type, and payment method to identify churn patterns.
- **Monthly and Total Charges**: Analyzes the relationship between charges and churn.

## Dashboard Visuals
Churn Dashboard
![image](https://github.com/shakir-flash/Customer-Churn-Analysis-using-Power-BI/assets/59859522/39d527dd-e312-4a54-9441-d1c2b30610bd)

Customer Risk Analysis Dashboard
![image](https://github.com/shakir-flash/Customer-Churn-Analysis-using-Power-BI/assets/59859522/50a66da4-e1fb-4df8-9ba7-140b6ef05dc9)


## How to Use
1. **Open the Power BI file**: `Customer Churn Analysis Dashboard.pbix` in Power BI Desktop.
2. **Load the Data**: Ensure that `Customer Churn-Dataset.xlsx` is in the same directory as the `.pbix` file or update the data source path in Power BI.
3. **Explore the Dashboard**: Interact with the various charts and filters to gain insights into customer churn.

## Conclusion
This dashboard provides valuable insights into the factors contributing to customer churn. By understanding these factors, businesses can develop strategies to reduce churn and improve customer retention.

## Future Work
- **Enhance Data Quality**: Further clean and preprocess the data to improve analysis accuracy.
- **Predictive Modeling**: Incorporate machine learning models to predict future churn.
- **Real-Time Data**: Integrate real-time data for continuous monitoring and analysis.
