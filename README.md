# 📊 Customer Behavior Analysis – Statistics Project

## 📌 Project Overview

This project focuses on analyzing customer behavior using statistical and mathematical techniques in Python.

The main objective is to understand customer purchasing patterns and identify factors related to customer spending, churn, customer segments, regions, product categories, and campaign groups.

The project was completed as part of a Statistics assignment and uses Python for data analysis, visualization, and statistical testing.

---

## 🎯 Objectives

The project aims to answer the following questions:

1. What are the average, median, and mode of `PurchaseAmount`?
2. Are there any outliers in the `PurchaseAmount` data?
3. Is there any skewness or kurtosis in the `PurchaseAmount` distribution?
4. Is there a significant difference in spending between male and female customers?
5. Is there a relationship between `ProductCategory` and customer churn?
6. Does `PurchaseAmount` vary significantly across different regions?
7. Which email campaign (A or B) has the higher average `PurchaseAmount`?
8. Is the `PurchaseAmount` distribution approximately normally distributed?
9. What insights can be gained by applying the Central Limit Theorem?
10. What is the 95% confidence interval for the average `PurchaseAmount`?

---

## 📂 Dataset

The dataset contains **5,000 customer records** and **7 variables**.

### Dataset Columns

| Column | Description |
|---|---|
| `CustomerID` | Unique customer identification number |
| `Gender` | Customer gender |
| `Region` | Customer's geographical region |
| `PurchaseAmount` | Amount spent by the customer |
| `ProductCategory` | Category of the purchased product |
| `Churn` | Whether the customer has churned (Yes/No) |
| `CampaignGroup` | Email campaign group (A/B) |

### Dataset Size

- **Rows:** 5,000
- **Columns:** 7
- **Numerical variable:** `PurchaseAmount`
- **Categorical variables:** Gender, Region, ProductCategory, Churn, CampaignGroup

---

## 🛠️ Technologies & Libraries Used

The project was developed using Python and Jupyter Notebook.

### Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy

### Main statistical techniques

- Descriptive Statistics
- Interquartile Range (IQR)
- Outlier Detection
- Skewness
- Kurtosis
- Independent Two-Sample t-test
- Chi-Square Test of Independence
- One-Way ANOVA
- Q-Q Plot
- Shapiro-Wilk Normality Test
- Central Limit Theorem
- Confidence Interval Estimation

---

## 🔍 Analysis Performed

### 1. Descriptive Statistics

Calculated:

- Mean
- Median
- Mode
- Standard deviation
- Minimum and maximum values
- Quartiles

For `PurchaseAmount`, the dataset contains **4,850 non-missing observations**.

The observed mean purchase amount is approximately **1003.95**.

---

### 2. Outlier Detection

The Interquartile Range (IQR) method was used to identify unusual purchase amounts.

The analysis calculated:

```text
Q1
Q3
IQR
Lower Bound
Upper Bound
