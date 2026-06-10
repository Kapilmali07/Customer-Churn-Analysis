# Customer-Churn-Analysis

## Overview

This project focuses on analyzing customer churn behavior in a telecom dataset using Python. The objective of the project is to identify patterns, trends, and factors influencing customer churn through data cleaning, exploratory data analysis (EDA), and data visualization.

The project helps understand customer retention challenges and provides business insights to reduce churn.

---

## Dataset

* Dataset Type: Telecom Customer Churn Dataset
* Total Records: 7,043 customers
* Features: 21 columns including customer demographics, internet services, payment methods, tenure, monthly charges, and churn status.

Key columns:

* Gender
* SeniorCitizen
* InternetService
* OnlineSecurity
* TechSupport
* Contract
* MonthlyCharges
* TotalCharges
* Churn

---

## Tools & Libraries Used

### Programming Language

* Python

### Libraries

* Pandas
* NumPy
* Matplotlib
* Seaborn

### Development Environment

* Jupyter Notebook

---

## Project Workflow

### 1. Data Loading

* Imported the dataset using Pandas
* Checked dataset structure and column information

### 2. Data Cleaning

* Replaced blank values in `TotalCharges`
* Converted data types for analysis
* Checked missing values and duplicates
* Standardized data for better visualization

### 3. Exploratory Data Analysis (EDA)

Performed detailed analysis to understand:

* Customer churn distribution
* Churn by gender and senior citizens
* Impact of internet services on churn
* Customer behavior based on contracts and payment methods
* Relationship between additional services and churn

### 4. Data Visualization

Created visualizations using Matplotlib and Seaborn:

* Count Plots
* Pie Charts
* Histograms
* Stacked Bar Charts

These charts helped identify high-risk customer segments and important churn drivers.

---

## Key Insights

* Approximately 26% of customers churned from the service.
* Fiber Optic customers showed the highest churn rate.
* Customers without Online Security and Tech Support were more likely to churn.
* Long-term contract customers had lower churn rates.
* Add-on services improved customer retention.

---

## Sample Analysis

### Customer Churn Distribution

---

## Project Structure

```bash id="2rt9qz"
Customer-Churn-Analysis/
│
├── Dataset/
├── Jupyter Notebook/
├── Visualizations/
├── Reports/
└── README.md
```

* Open Jupyter Notebook
* Run all cells sequentially
* Explore charts and insights

---

## Business Recommendations

* Improve retention strategies for Fiber Optic customers
* Promote add-on services like Online Security and Tech Support
* Create personalized offers for high-risk customers
* Improve overall customer service experience

---

## Author

**Kapil Sanjay Mali**
Data Analyst | Python | SQL | Excel | Power BI
LinkedIn: https://www.linkedin.com/in/kapil-mali/
GitHub: https://github.com/Kapilmali07 
