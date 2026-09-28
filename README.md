# Customer-Churn-Detection
Customer Churn Detection — A data analytics project using Python, and statistics to investigate customer churn, identify key churn patterns, visualize insights, and develop data-backed business recommendations.
# Customer Churn Analysis

## 📊 Project Overview

Customer churn is an important business challenge that can directly affect customer retention and revenue. This project performs **Exploratory Data Analysis (EDA)** on customer data to understand churn patterns, customer behavior, and the factors associated with customers leaving a service.

The analysis uses Python-based data analysis and visualization techniques to transform raw customer data into meaningful and actionable insights.

## 🎯 Objectives

* Understand the overall customer churn distribution.
* Explore customer demographics and subscription patterns.
* Analyze the relationship between churn and monthly charges.
* Study customer usage behavior and tenure.
* Examine the impact of support calls and satisfaction levels.
* Identify patterns and relationships between numerical variables.
* Present insights using clear and informative visualizations.

## 📁 Dataset

The dataset contains **305 customer records initially**, with **12 variables**:

| Column          | Description                           |
| --------------- | ------------------------------------- |
| Customer_ID     | Unique customer identifier            |
| Age             | Customer age                          |
| Gender          | Customer gender                       |
| Location        | Customer location                     |
| Subscription    | Subscription plan                     |
| Tenure_Months   | Duration of customer subscription     |
| Monthly_Charges | Monthly customer charges              |
| Usage_Hours     | Customer usage hours                  |
| Support_Calls   | Number of support calls               |
| Satisfaction    | Customer satisfaction score           |
| Payment_Method  | Customer payment method               |
| Churn           | Whether the customer left the service |

## 🛠️ Technologies Used

* **Python**
* **Pandas** – Data manipulation and analysis
* **NumPy** – Numerical operations
* **Matplotlib** – Data visualization
* **Seaborn** – Statistical visualization
* **Jupyter Notebook** – Analysis environment

## 🔍 Data Cleaning

The dataset was inspected for missing values and duplicate records.

### Missing Values

Missing values were handled using:

* **Age:** Filled using the mean.
* **Satisfaction:** Filled using the median.
* **Subscription:** Filled using the mode.

The analysis also identified **5 duplicate records**, which were removed, reducing the dataset from **305 to 300 customers**.

## 📈 Exploratory Data Analysis

The project analyzes:

### Customer Churn Distribution

Out of the 300 customers after cleaning:

* **224 customers** did not churn.
* **76 customers** churned.
* Overall churn rate: **25.33%**.

### Subscription Analysis

Churn was compared across:

* Basic
* Standard
* Premium

The analysis uses cross-tabulation and visualization to examine how churn varies between subscription types.

### Location Analysis

Customer churn was also examined across:

* Calicut
* Kannur
* Kochi
* Thrissur
* Trivandrum

### Customer Behavior

The project compares churned and non-churned customers based on:

* Support calls
* Satisfaction
* Usage hours
* Tenure
* Monthly charges

### Correlation Analysis

A correlation matrix and heatmap were created to examine relationships between numerical variables including:

* Age
* Tenure
* Monthly Charges
* Usage Hours
* Support Calls
* Satisfaction

## 📊 Visualizations

The project includes several visualizations:

* Customer churn distribution
* Churn by subscription type
* Monthly charges vs churn
* Usage hours vs churn
* Correlation heatmap
* Statistical comparisons using box plots and count plots

## 💡 Key Findings

The analysis identified several notable patterns:

* The overall customer churn rate in the cleaned dataset is **25.33%**.
* Churned customers have a slightly higher average number of support calls (**2.88**) compared with non-churned customers (**2.50**).
* Churned customers have a lower average satisfaction score (**4.99**) compared with non-churned customers (**5.53**).
* Average usage is lower among churned customers (**24.40 hours**) than non-churned customers (**28.41 hours**).
* Average tenure is slightly lower for churned customers (**23.03 months**) than non-churned customers (**24.86 months**).

These findings highlight how customer engagement, satisfaction, and support interactions can be useful areas for further churn investigation.

## 🚀 Project Workflow

```text
Raw Customer Data
        ↓
Data Loading
        ↓
Data Inspection
        ↓
Missing Value Treatment
        ↓
Duplicate Removal
        ↓
Descriptive Statistics
        ↓
Exploratory Data Analysis
        ↓
Data Visualization
        ↓
Correlation Analysis
        ↓
Business Insights
```

## 📌 Conclusion

This project demonstrates how **Exploratory Data Analysis can be used to understand customer churn and uncover meaningful patterns within customer data**. Through data cleaning, statistical analysis, visualization, and correlation analysis, the project provides a clear view of customer behavior and potential areas that may require further investigation for improving customer retention.

## 👨‍💻 Author

**Riswan CK**

Data Science Enthusiast | Python | SQL | Power BI | Excel

---

⭐ If you found this project useful, consider giving the repository a star!
