# 🏦 Loan Approval Prediction  
### 📊 A Complete Machine Learning Workflow for Binary Classification

This project uses the **Loan-Approval-Prediction-Dataset** to build and evaluate models that predict whether a loan application will be approved or rejected. The notebook walks through a full machine learning pipeline—from data exploration to model evaluation—designed to be both educational and portfolio-ready.

---

##  Workflow Overview

1. **Data Exploration**  
   - Summary statistics and missing value analysis  
   - Class distribution and feature overview

2.  **Data Visualization**  
   - `Pair Plot`: Visual relationships between key financial features  
   - `Heatmap`: Correlation matrix to identify strong predictors  
   - `Boxplot`: Distribution of loan amounts across approval status  
   - `Pie Chart`: Proportion of approved vs rejected loans  
   - `Countplot`: Final comparison of model performance (Logistic Regression, Random Forest, Gradient Boosting)

3. **Data Transformation**  
   - Encoding categorical variables  

4.  **Modeling & Evaluation**  
   - Trained and compared three models:
     - Logistic Regression
     - Random Forest Classifier
     - Gradient Boosting Classifier  
   - Evaluated using precision, recall, F1-score, and accuracy  
   - Visual comparison of model metrics included

---

## Model Comparison Summary

| Model                  | Accuracy | F1-Score (Class 0) | F1-Score (Class 1) |
|------------------------|----------|--------------------|--------------------|
| Logistic Regression    | 0.81     | 0.72               | 0.86               |
| Random Forest          | 0.98     | 0.98               | 0.98               |
| Gradient Boosting      | 0.98     | 0.98               | 0.99               |

---

## 📊 Key Visualizations

Here are a few charts that highlight important insights from the project
**العربية:** يوضح العلاقات بين المتغيرات ويساعد في تحديد المؤشرات القوية.
![Heatmap](images/heatmap.png) 
**العربية:** مقارنة النماذج النهائية باستخدام Countplot لعرض الدقة.

![Model Comparison](images/model_comparison.png)

---

## 💡 Author

**Esraa** — Passionate about making tech accessible, building reproducible workflows, and empowering learners through clear documentation and visual storytelling.
