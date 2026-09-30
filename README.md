# Customer Retention & Churn Analysis

## Future Interns – Data Science & Analytics Task 2

This project analyzes customer churn, retention patterns, customer lifetime, and factors associated with customer churn using Python and Power BI.

## Objective

The objective of this project is to understand:
- Customer churn and retention patterns
- Customer lifetime and tenure
- Churn across different customer segments
- Factors associated with higher or lower churn
- Business actions that can support customer retention

## Tools Used

- Python
- Pandas
- Jupyter Notebook
- Power BI
- Excel/CSV Dataset

## Dataset

The analysis uses the Telco Customer Churn dataset containing customer demographics, services, contract details, tenure, charges, payment methods, and churn information.

After cleaning, the dataset contains **7,032 customers**.

## Data Cleaning

The following steps were performed using Python:
- Converted `TotalCharges` into numeric format
- Identified 11 records with missing `TotalCharges`
- Verified that these records had zero tenure
- Removed the 11 incomplete records
- Created tenure and monthly charge groups for analysis

## Key Analysis

The project analyzed:
- Overall churn rate
- Churn by contract type
- Churn by tenure group
- Churn by internet service
- Churn by payment method
- Churn by technical support availability
- Average tenure and monthly charges

## Key Insights

- Overall customer churn rate is **26.58%**.
- Month-to-month customers have a substantially higher observed churn rate than customers on one-year or two-year contracts.
- Customers with shorter tenure show higher observed churn than long-tenure customers.
- The Fiber optic customer segment has a higher observed churn rate than DSL and customers without internet service.
- Customers using Electronic Check show the highest observed churn among payment methods.
- Customers with Tech Support show lower observed churn than customers without Tech Support.
- Churned customers have a lower average tenure than retained customers.

These findings describe associations in the dataset and do not by themselves establish causation.

## Power BI Dashboard

The Power BI dashboard presents:
- Total Customers
- Churned Customers
- Churn Rate
- Average Tenure
- Average Monthly Charges
- Churn by Contract
- Churn by Tenure
- Churn by Internet Service
- Churn by Payment Method
- Churn by Tech Support

## Dataset Limitation

The dataset does not contain an actual customer signup date. Therefore, true signup-month cohort analysis could not be performed. Tenure-based customer lifetime segmentation was used instead.

## Project Files

- `FUTURE_DS_02.ipynb` – Python data cleaning and analysis
- `Telco_Churn_Cleaned.csv` – cleaned dataset
- `FUTURE_DS_02.pbix` – Power BI dashboard

## Internship

**Future Interns – Data Science & Analytics Internship**

**Task 2: Customer Retention & Churn Analysis**
