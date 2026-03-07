# Customer Churn Prediction

## Week 1 & Week 2: EDA + Machine Learning Models

### 📌 Course Information

* **Course:** Introduction to Applied Artificial Intelligence
* **Semester:** BS 8th Semester
* **Project:** Customer Churn Prediction
* **Author:** Wayna Ali
* **Date:** 04/03/2026

---

## 📊 Project Overview

This project focuses on performing **Exploratory Data Analysis (EDA)** and **building predictive models** on the Telco Customer Churn dataset.

**Goals:**

* Understand customer behavior patterns
* Identify factors contributing to churn
* Build machine learning models to predict churn
* Discover high-risk customer groups
* Prepare actionable business insights

---

## 📂 Dataset Information

* **Source:** Telco Customer Churn Dataset (Kaggle)
* **Total Customers:** 7,043
* **Total Features:** 21
* **Target Variable:** `Churn` (Yes/No)

⚠️ Note: The dataset file (`customer_data.csv`) is not included in this repository.
Please download it from Kaggle and place it in the project folder before running the notebooks.

---

## 📁 Repository Structure

* `week1_eda.ipynb` → Exploratory Data Analysis notebook
* `week2_ml_models.ipynb` → Machine learning models for churn prediction
* `README.md` → Project documentation
* `.gitignore` → Excludes unnecessary files

---

## 🔍 Key Insights

**Week 1: EDA**

* Customers with **month-to-month contracts** have significantly higher churn rates.
* Customers with **short tenure (< 6 months)** are more likely to churn.
* Higher **Monthly Charges** are associated with increased churn.
* **Fiber optic internet users** show higher churn compared to DSL users.
* Customers using **electronic check payment method** have higher churn rates.

**Week 2: ML Models**

* Trained and compared multiple machine learning models:

  * **Logistic Regression**
  * **Decision Tree Classifier**
  * **Random Forest Classifier**
  * **XGBoost Classifier**
* Evaluated models using:

  * Accuracy, Precision, Recall, F1-score
  * Confusion Matrix
  * ROC-AUC Curve
* **Random Forest and XGBoost** showed the best performance in predicting customer churn.

| Model               | Accuracy | Precision | Recall | F1-score |
| ------------------- | -------- | --------- | ------ | -------- |
| Logistic Regression | 0.79     | 0.70      | 0.63   | 0.66     |
| Decision Tree       | 0.78     | 0.68      | 0.64   | 0.66     |
| Random Forest       | 0.83     | 0.75      | 0.70   | 0.72     |
| XGBoost             | 0.84     | 0.76      | 0.71   | 0.73     |

---

## ⚙️ Setup Instructions

Install required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost jupyter
```

Run the notebooks:

```bash
jupyter notebook week1_eda.ipynb
jupyter notebook week2_ml_models.ipynb
```

---

## 🚀 Next Steps

* Week 3: Model evaluation and optimization
* Week 4: Deployment and dashboard development

---

## 🎯 Learning Outcomes

Through this project, I developed skills in:

* Data cleaning and preprocessing
* Exploratory Data Analysis (EDA)
* Data visualization using Matplotlib and Seaborn
* Building and comparing machine learning models (Logistic Regression, Decision Tree, Random Forest, XGBoost)
* Evaluating model performance metrics
* Identifying business insights from data
* Git and GitHub version control workflow

---

## 📬 Contact

* LinkedIn: [Wayna Ali](https://www.linkedin.com/in/wayna-ali-055204209/)
* GitHub: [waynaali](https://github.com/waynaali)


Do you want me to do that?
