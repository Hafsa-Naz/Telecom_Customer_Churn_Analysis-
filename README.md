# Customer Churn Analysis Project

This project analyzes customer churn data and visualizes patterns to understand why customers leave a company. The analysis is performed using Python, with various libraries for data manipulation and visualization.

---

##  Project Overview

Customer churn refers to the percentage of customers who stop using a company's services during a certain period. This project explores a dataset of telecom customers and investigates factors affecting churn, such as contract type, payment method, tenure, and services used.

Key steps performed in this project:

- Data Import and Inspection
- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Visualization of churn trends based on different factors
- Insights and conclusions

---

## Dataset

The dataset used is `Customer Churn.csv` with 7043 records and 21 columns, including:

| Column | Description |
|--------|-------------|
| customerID | Unique ID for each customer |
| gender, SeniorCitizen, Partner, Dependents | Customer demographic info |
| tenure | Months with the company |
| PhoneService, MultipleLines, InternetService | Service information |
| OnlineSecurity, OnlineBackup, DeviceProtection, TechSupport, StreamingTV, StreamingMovies | Additional services |
| Contract, PaperlessBilling, PaymentMethod | Contract and billing info |
| MonthlyCharges, TotalCharges | Billing amounts |
| Churn | Target variable (Yes / No) |

---

## Libraries & Tools

- **Programming Language:** Python  
- **Libraries:** pandas, numpy, matplotlib, seaborn  
- **Tools:** Jupyter Notebook  

---

## Data Cleaning & Preprocessing

- Checked for missing values and duplicates  
- Converted `TotalCharges` to float  
- Converted `SeniorCitizen` from 0/1 to "Yes"/"No"  
- Ensured all categorical columns are ready for visualization  

---

## Exploratory Data Analysis (EDA)

- **Churn Distribution:** ~26.5% of customers churned  
- **Gender vs Churn:** Gender has minimal impact  
- **Senior Citizens:** Higher churn among senior citizens  
- **Tenure:** Short-term customers churn more  
- **Contract:** Month-to-month contracts show highest churn  
- **Payment Method:** Customers paying by electronic check churn more  
- **Additional Services:** Tech support, online security, and long-term contracts help reduce churn  

**Visualizations:**

- Countplots for churn by gender, senior citizens, contract type, payment method, and services  
- Pie chart showing churn percentage  
- Stacked bar charts for senior citizen churn percentage  
- Histogram for tenure vs churn  

---

## Key Insights

- Senior citizens and single customers are more likely to churn  
- Month-to-month contracts have the highest churn rate  
- Customers using fiber optic internet and paying via electronic check churn more often  
- Offering additional services like tech support and online security helps retain customers  

---

## Author

**Hafsa Naz** – 
BS Artificial Intelligence Student
Dawood University of Engineering & Technology  
[LinkedIn Profile](https://www.linkedin.com/in/hafsa-naz-/)
