# College Application Prediction using Machine Learning (R)

## 📌 Project Overview
This project applies **regression-based machine learning models in R** to predict a continuous college application–related outcome.  
It was completed as a **course project for a Data Science certification**.

The focus of the project is on **model comparison** and **error distribution analysis**, rather than only point accuracy.

---

## 📊 Dataset
- Source: https://rdrr.io/cran/ISLR/man/College.html
- Format: CSV
- Description: See `data/data_description.txt`

The dataset includes academic and institutional features relevant to college application outcomes.

---

## 🧠 Methods & Models
The following **regression models** were implemented and compared:

- Classical Linear Regression  
- Decision Tree Regression  
- Random Forest Regression  
- XGBoost Regression  
- Ridge Regression  
- Lasso Regression  

Each model was trained using the same preprocessing pipeline to ensure fair comparison.

---

## 📐 Evaluation Metrics
Model performance was evaluated using **absolute error–based statistics**:

- Mean Absolute Error  
- Median Absolute Error  
- Interquartile Range (IQR) of Absolute Error  
- Minimum Absolute Error  
- Maximum Absolute Error  

These metrics were selected to better capture **error distribution and robustness**, not only average performance.

---

## 🛠 Tools & Technologies
- R
- R Markdown
- caret
- ggplot2
- xgboost

---

## 📈 Results
- Model comparisons and evaluation results are documented in the rendered HTML report.
- Summary tables and visualizations are available in the `results/` folder.

---

## 📁 Repository Structure
- data/ → Dataset and data description
- notebooks/ → R Markdown source and rendered HTML
- results/ → Figures and performance summaries
---

## 📌 Notes
This project demonstrates:
- End-to-end regression modeling in R
- Comparison of classical, regularized, tree-based, and ensemble models
- Use of distribution-based error metrics for model evaluation
- Reproducible analysis and reporting


