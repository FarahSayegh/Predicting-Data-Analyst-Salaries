# 📊 Predicting Data Analyst Salaries

This project aims to analyze and predict data analyst salaries using machine learning techniques and extensive data preprocessing. The work was conducted as part of a university course at Damascus University, Faculty of Informatics Engineering, Department of Artificial Intelligence.

## ✨ Project Overview

In the current job market, the demand for data analysts is increasing significantly. This project explores:

- 🔍 **Data exploration** of a dataset sourced from Kaggle and Glassdoor
- 🧹 **Data preprocessing**: handling missing values, feature engineering, encoding categorical variables
- 📈 **Exploratory Data Analysis (EDA)**: discovering patterns in job titles, required skills, salary distributions, and company characteristics
- 🤖 **Machine Learning modeling**: comparing various regression models to predict average salaries

The main goal is to understand the factors affecting data analyst salaries and build a model that predicts salary ranges based on job features.

## 📂 Dataset

The dataset was collected from [Kaggle](https://www.kaggle.com/datasets/andrewmvd/data-analyst-jobs/data) and contains over 2200 job postings with features like:

- `job_title`
- `salary_estimate`
- `company_name`
- `location`
- `headquarters`
- `industry`
- `sector`
- `revenue`
- `job_description`
- … and more.

## 📝 Methodology

The project followed these steps:

1. **Data Cleaning:**
   - Dropped irrelevant columns
   - Filled missing values using logical imputation
   - Standardized categorical values
   - Engineered new features (e.g., min/max/average salary, company age)

2. **Feature Engineering:**
   - Extracted required skills from job descriptions (Python, SQL, Excel, Tableau…)
   - Created binary columns for skill presence
   - Binned numeric variables for better interpretation

3. **EDA:**
   - Visualized distributions of salaries, company sizes, ratings
   - Analyzed the correlation between salary and factors like skills, industry, state

4. **Modeling:**
   - Applied and tuned multiple regression models:
     - Linear Regression
     - Ridge, Lasso, ElasticNet
     - Decision Tree, Random Forest
     - Gradient Boosting, XGBoost
     - SVR, KNN
   - Evaluated using R², MAE on train/test splits

## 🏆 Results

✅ **Random Forest**, **Gradient Boosting**, and **XGBoost** achieved the best predictive performance, with XGBoost providing an R² of ~0.3965 on the test set.

Key insights include:

- Higher salaries are associated with skills like **Python**, **Tableau**, and **R**
- Location and company industry significantly affect salary
- Educational degree requirements have a marginal impact on salary averages

## 📌 Technologies Used

- Python 3
- NumPy, Pandas
- Scikit-learn
- Matplotlib, Seaborn
- WordCloud
- Mlxtend
- XGBoost

## 📚 References

Several resources were consulted, including Kaggle notebooks and research papers. See the full list of references in the PDF report.

---
