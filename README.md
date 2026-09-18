# Employee Attrition Analysis

## 📌 Project Overview

Employee attrition is an important challenge for organizations because employee turnover can increase recruitment costs, affect productivity, and impact team performance.

This project analyzes employee data to identify patterns and factors associated with employee attrition. Exploratory Data Analysis (EDA), data visualization, machine learning, and Power BI are used to understand employee turnover and build a predictive model.

## 🎯 Objectives

* Analyze employee attrition patterns.
* Identify factors associated with employee turnover.
* Perform exploratory data analysis and visualization.
* Build a machine learning model to predict employee attrition.
* Evaluate model performance using classification metrics.
* Create an interactive Power BI dashboard.
* Generate useful business insights from the analysis.

## 📊 Dataset

The project uses the **IBM HR Analytics Employee Attrition & Performance** dataset.

The dataset contains **1,470 employee records and 35 attributes**, including:

* Age
* Department
* Job Role
* Job Satisfaction
* Monthly Income
* OverTime
* Years at Company
* Job Level
* Business Travel
* Work-Life Balance
* Attrition

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook
* Power BI
* GitHub

## 🔄 Project Workflow

1. Data Collection
2. Data Loading
3. Data Cleaning
4. Exploratory Data Analysis
5. Data Visualization
6. Feature Encoding
7. Train-Test Split
8. Feature Scaling
9. Machine Learning Model Development
10. Model Evaluation
11. Power BI Dashboard Creation
12. Business Insights

## 🔍 Exploratory Data Analysis

The analysis examined relationships between employee attrition and different factors such as:

* Overtime
* Job Role
* Job Satisfaction
* Age
* Monthly Income
* Job Level
* Years at Company

### Key Observations

* The overall observed attrition rate in the dataset is approximately **16.12%**.
* Employees working overtime showed a higher observed attrition rate than employees not working overtime.
* Employees with **0–2 years at the company** showed a higher observed attrition rate.
* Sales Representatives showed a relatively high observed attrition rate compared with several other job roles.

These observations describe patterns in the dataset and do not establish causal relationships.

## 🤖 Machine Learning

A **Logistic Regression** model was developed to predict employee attrition.

### Model Preparation

* Attrition was converted into a binary target:

  * `Yes = 1`
  * `No = 0`
* Categorical variables were converted using one-hot encoding.
* Numerical features were standardized using `StandardScaler`.
* The dataset was divided into training and testing sets using an **80:20 split**.

### Model Performance

The Logistic Regression model achieved:

**Accuracy: 88.44%**

Classification results showed that the model performed better at identifying employees who stayed than employees who left.

Because the dataset contains fewer attrition cases than non-attrition cases, accuracy alone should not be used to judge the model.

## 📈 Power BI Dashboard

An interactive Power BI dashboard was created to provide a visual overview of employee attrition.

The dashboard includes:

* Total Employees
* Employees Left
* Attrition Rate
* Attrition by Department
* Attrition by Job Role
* Attrition by Overtime
* Attrition by Age

### Dashboard Summary

* **Total Employees:** 1,470
* **Employees Left:** 237
* **Observed Attrition Rate:** 16.12%

## 💡 Business Insights

The analysis can help organizations:

* Identify employee groups with higher observed attrition.
* Monitor overtime-related attrition patterns.
* Understand attrition across different job roles.
* Examine early-tenure employee turnover.
* Support data-driven employee retention strategies.

## 🚀 Future Scope

Future improvements could include:

* Testing additional machine learning algorithms.
* Hyperparameter tuning.
* Handling class imbalance using suitable techniques.
* Feature importance analysis.
* Deploying the prediction model as a web application.
* Connecting Power BI to regularly updated employee data.
* Building an automated employee attrition monitoring system.

## 📁 Project Structure

```text
Employee_Attrition_Analysis/
│
├── Employee_Attrition_Analysis.ipynb
├── README.md
└── data/
    └── HR Analytics Employee Attrition Dataset
```

## 👩‍💻 Author

**N. Keerthi**

B.Tech — Artificial Intelligence & Machine Learning

---

⭐ This project was developed as part of a **Data Analyst Internship at CodeC Technologies**.
