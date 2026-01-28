# IBM HR Analytics: Employee Attrition Analysis 📊

**Author**: Hacer Özkan  
**Project Date**: January 2026  
**Language**: R  
**Dataset**: [IBM HR Analytics Attrition Dataset](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)

---

## 📌 Project Overview
This project aims to identify and analyze the key factors that lead to employee attrition at IBM. By leveraging statistical modeling and data visualization, we seek to understand why employees leave and provide actionable business recommendations to improve retention.

## 🛠 Technologies & Libraries
* **R Programming**
* **Tidyverse** (Data manipulation and visualization)
* **ggplot2** (Advanced plotting)
* **corrplot** (Correlation analysis)
* **Statistical Tests**: T-test, ANOVA, Chi-Square, Logistic Regression

---

## 🔍 Key Findings

### 1. Workload & Overtime ⚠️
Our **Chi-Square test ($p < 2.2 \times 10^{-16}$)** and **Logistic Regression** confirm that **Overtime** is the single strongest predictor of attrition. Employees working extra hours show a dramatically higher turnover rate.

### 2. Financial Compensation 💸
A **T-test** revealed a significant pay gap between those who stay and those who leave ($p < 0.05$). On average, employees who resigned were earning **$2,045 less** per month than those who remained.

### 3. Leadership & Management 👥
Analysis shows that employees who left had significantly shorter relationships with their current managers (avg. **2.85 years**) compared to those who stayed (avg. **4.37 years**).

### 4. Commute Distance 🏠
Longer commutes are statistically associated with higher attrition. The probability of leaving increases as the distance from home to the office grows.

---

## 💡 Business Recommendations
* **Workload Management:** Reduce mandatory overtime and monitor employee burnout.
* **Compensation Benchmarking:** Regularly review salary structures for junior and mid-level roles.
* **Leadership Training:** Invest in manager-employee engagement programs.
* **Flexibility:** Offer remote work or flexible scheduling for employees with long commutes.

---

## 🚀 How to Run the Analysis
1. Clone this repository.
2. Ensure you have R and the necessary libraries installed (`tidyverse`, `corrplot`, `scales`, `dplyr`).
3. Open the `.ipynb` file in RStudio or Kaggle.
