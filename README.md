# Banking Customer Churn Analysis 📊

##  Project Overview
This project focuses on understanding **customer churn in banking institutions** through Exploratory Data Analysis (EDA). The dataset includes customer demographics, banking behaviors, and financial indicators. The goal is to identify factors that influence churn and provide actionable insights to reduce customer attrition.

---

## 🗂️ Dataset
- **Rows:** 10,000  
- **Columns:** 14  
- Features include customer demographics (Age, Gender, Geography), account details (Balance, Tenure, Number of Products), and churn indicator (`Exited`).

---

##  Problem Statement
Banking institutions face significant losses due to customer churn. This project analyzes key patterns in customer behavior to identify which groups are more likely to leave and how churn can be minimized.

---

##  Exploratory Data Analysis (EDA)
Basic Insights
1. What is the distribution of target variable (Exited)?
2. What is the average age, balance, salary, and credit score of customers who exited vs retained?
3. What is the gender distribution and does it impact churn?
4. Which geography (France, Spain, Germany, etc.) has higher churn?
Behavioral Insights
5. Does tenure (years with bank) affect churn?
6. Does having a credit card reduce churn?
7. Do active members churn less than inactive ones?
8. How does the number of products relate to churn?
Financial Insights
9. Is there a relation between balance & churn?
10. Is estimated salary related to churn?
11. Which credit score range has the highest churn?

---

## 📊 Visualizations
The analysis includes:
- Pie charts (churn distribution)  
- Bar plots (churn by gender, geography, products, credit card usage)  
- KDE plots (balance vs churn, age distribution)  
- Count plots (active members vs churn)  

---

## Results & Insights
- Churn rate is around **20%**, showing a significant risk for banks.  
- **Inactive customers** and those with **high balances but low engagement** are more likely to churn.  
- Geography and age significantly influence churn patterns.  

---

## 📂 Files in Repository
- `Banking_Customer_churn_Analysis.ipynb` → Main EDA notebook  
- `Banking_Customer_Churn_Analysis_insights.pdf` → Project report
- `Dataset - Banking_Customers`  
- `README.md` → Project documentation  

---

##  Tools & Libraries
- Python (Pandas, Numpy, Matplotlib, Seaborn)  
- Jupyter Notebook / Google Colab  
- ReportLab (for PDF generation)  

---

## ✅ Conclusion
This EDA highlights key drivers of churn in banking customers. The findings can guide retention strategies and form the basis for predictive modeling.

---
