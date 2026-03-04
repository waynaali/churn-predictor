# Customer Churn Prediction  
## Week 1: Exploratory Data Analysis (EDA)

### 📌 Course Information
- **Course:** Introduction to Applied Artificial Intelligence  
- **Semester:** BS 8th Semester  
- **Project:** Customer Churn Prediction  
- **Author:** Wayna Ali 
- **Date:** 04/03/2026

---

## 📊 Project Overview

This project focuses on performing **Exploratory Data Analysis (EDA)** on the Telco Customer Churn dataset.  

The goal of this analysis is to:
- Understand customer behavior patterns  
- Identify factors contributing to churn  
- Discover high-risk customer groups  
- Prepare insights for machine learning model development in upcoming weeks  

This notebook serves as the foundation for future predictive modeling.

---

## 📂 Dataset Information

- **Source:** Telco Customer Churn Dataset (Kaggle)  
- **Total Customers:** 7,043  
- **Total Features:** 21  
- **Target Variable:** `Churn` (Yes/No)

⚠️ Note: The dataset file (`customer_data.csv`) is not included in this repository.  
Please download it from Kaggle and place it in the project folder before running the notebook.

---

## 📁 Repository Structure

- `week1_eda.ipynb` → Complete exploratory data analysis notebook  
- `README.md` → Project documentation  
- `.gitignore` → Excludes unnecessary files  

---

## 🔍 Key Insights

- Customers with **month-to-month contracts** have significantly higher churn rates.
- Customers with **short tenure (< 6 months)** are more likely to churn.
- Higher **Monthly Charges** are associated with increased churn.
- **Fiber optic internet users** show higher churn compared to DSL users.
- Customers using **electronic check payment method** have higher churn rates.

---

## 📈 Analysis Performed

- Dataset overview and missing value analysis  
- Numerical feature exploration (Tenure, MonthlyCharges, TotalCharges)  
- Categorical feature analysis (Contract, InternetService, PaymentMethod)  
- Churn distribution and percentage calculation  
- Correlation analysis and heatmap visualization  
- Feature relationship visualizations  

Total visualizations: **6–8 plots**

---

## ⚙️ Setup Instructions

Install required libraries:

```bash
pip install pandas numpy matplotlib seaborn jupyter
````

Run the notebook:

```bash
jupyter notebook week1_eda.ipynb
```

---

## 🚀 Next Steps

* Week 2: Build machine learning models
* Week 3: Model evaluation and optimization
* Week 4: Deployment and dashboard development

---

## 🎯 Learning Outcomes

Through this project, I developed skills in:

* Data cleaning and preprocessing
* Exploratory Data Analysis (EDA)
* Data visualization using Matplotlib and Seaborn
* Identifying business insights from data
* Git and GitHub version control workflow

---

## 📬 Contact
linkedin: https://www.linkedin.com/in/wayna-ali-055204209/
github: https://github.com/waynaali

