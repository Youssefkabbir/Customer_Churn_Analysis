# Customer Churn Analysis Project
<p align="center">
  <img src="https://github.com/Youssefkabbir/Customer_Churn_Analysis/blob/main/customerchurn.jpeg" alt="Dashboard Screenshot">
</p>

## Overview
This project is divided into two parts:
1. **Power BI Dashboard** - A visual analysis of customer churn using Power BI.
2. **Predictive Modeling with Machine Learning** - Building a predictive model to identify potential churn using machine learning.

---

## Part 1: Power BI Dashboard
<p align="center">
  <img src="https://github.com/Youssefkabbir/Customer_Churn_Analysis/blob/main/Customer_churn_Analysis.png" alt="Dashboard Screenshot">
</p>

### **Objective**
The Power BI dashboard provides an in-depth analysis of customer churn by visualizing key metrics and trends. It helps in understanding customer behavior, churn patterns, and factors affecting churn rates.

### **Dashboard Features**
The Power BI dashboard consists of the following sections:

- **Filters & Slicers:**
  - Country filter to analyze churn across different regions.
  - Gender filter to compare churn rates between male and female customers.
  - Churn status filter to differentiate between churned and retained customers.

- **Customer Analysis by Age Group:**
  - A bar chart representing customer count across different age groups.
  - A line chart showing the churn rate for each age group.

- **Churn Rate by Age Groups and Activity Status:**
  - A stacked bar chart displaying changes in churn rate for various age groups based on activity status.

- **Churn Rate by Account Balance:**
  - A combination of bar and line charts showing customer count and churn rate across different account balance categories.

- **Churn Rate by Credit Card Ownership:**
  - A pie chart analyzing the churn rate between customers who own a credit card and those who do not.

- **Churn by Country:**
  - A geographic visualization displaying customer churn rates across different countries.

- **Tenure & Target Analysis by Age Groups:**
  - A line chart comparing the sum of tenure and the sum of target values for different age groups.

### **Technology Used**
- **Power BI Desktop** for data visualization.
- **DAX (Data Analysis Expressions)** for custom calculations and measures.
- **Data Transformation** using Power Query.

### **Insights from the Dashboard**
- Age groups **31-40 and 41-50** have the highest churn rate.
- Customers with a **low account balance** are more likely to churn.
- Active customers tend to have a lower churn rate compared to inactive ones.
- Credit card ownership does not significantly impact churn.
- Churn rate varies across different countries.

---

## Part 2: Predictive Modeling
<p align="center">
  <img src="https://github.com/Youssefkabbir/Customer_Churn_Analysis/blob/main/Python_code.png" alt="Python Screenshot">
</p>
In the second phase of this project, a **machine learning model** will be developed to predict customer churn. This will involve:

1. **Data Preprocessing:** Handling missing values, encoding categorical variables, and feature scaling.
2. **Exploratory Data Analysis (EDA):** Understanding data distributions, feature importance, and correlations.
3. **Model Selection:** Testing multiple models such as Logistic Regression, Random Forest, and XGBoost.
4. **Model Evaluation:** Using accuracy, precision, recall, and F1-score to evaluate performance.
5. **Deployment:** Deploying the predictive model for real-time churn prediction.

---

## Repository Structure
```plaintext
📂 Customer_Churn_Analysis
│── 📂 BI_Tools  # Contains Power BI reports and DAX formulas
│── 📂 Python        # Machine Learning scripts and Jupyter notebooks
│── README.md            # Project documentation
```

This README will be updated with details on the **predictive modeling phase** once it is implemented.

