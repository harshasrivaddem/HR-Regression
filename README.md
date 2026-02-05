# 👩‍💼 HR Employee Attrition Analysis using Logistic Regression

## 📌 Project Overview
This project analyzes an HR dataset to understand the factors that influence **employee attrition (employees leaving the company)** and builds a **Logistic Regression model** to predict whether an employee is likely to leave.

The goal is to use employee satisfaction, workload, evaluation, and tenure-related features to predict attrition.

---

## 📊 Dataset Description
- Dataset: `HR_comma_sep.csv`
- Rows: **14,999**
- Columns: **10**

### 🔑 Key Features
- `satisfaction_level` – Employee satisfaction score  
- `last_evaluation` – Performance evaluation score  
- `number_project` – Number of projects handled  
- `average_montly_hours` – Monthly working hours  
- `time_spend_company` – Years at company  
- `Work_accident` – Whether employee had a work accident  
- `promotion_last_5years` – Promotion in last 5 years  
- `Department` – Employee department  
- `salary` – Salary category  

### 🎯 Target Variable
- `left`
  - `1` → Employee left the company  
  - `0` → Employee stayed  

---

## 🛠️ Tools & Libraries Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

---

## 🔍 Exploratory Data Analysis (EDA)
- Inspected dataset structure and columns
- Visualized relationship between **number of projects** and **employee attrition**
- Identified key numerical features affecting employee turnover

---

## 🤖 Machine Learning Model
- **Algorithm:** Logistic Regression
- **Train-Test Split:** 80% training, 20% testing
- **Features Used:**
  - satisfaction_level
  - last_evaluation
  - number_project
  - average_montly_hours
  - time_spend_company
  - Work_accident

---

## 📈 Model Performance
- **Accuracy:** **77.1%**

```python
reg.score(X_test, y_test)
# Output: 0.771
