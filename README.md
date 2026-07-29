# Employee Attrition Prediction using Logistic Regression

<div align="center">

![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Scientific%20Computing-013243?logo=numpy)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-F7931E?logo=scikit-learn)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-blue)
![Status](https://img.shields.io/badge/Project-Completed-success)

</div>

---

# Project Overview

Employee attrition is one of the biggest challenges faced by Human Resource (HR) departments. Losing experienced employees increases recruitment costs, onboarding time, and decreases overall productivity.

The objective of this project is to build a **Machine Learning Classification Model** capable of predicting whether an employee is likely to leave the company based on demographic, work-related, and satisfaction-related attributes.

The model is built using **Logistic Regression**, a widely used classification algorithm for binary prediction problems.

---

# Business Problem

Hiring new employees is expensive.

If organizations can identify employees who are likely to leave before they resign, HR teams can take proactive measures such as:

- Career Development
- Salary Review
- Internal Transfers
- Better Work-Life Balance
- Employee Engagement Programs

Machine Learning helps transform historical employee data into actionable business insights.

---

# Dataset Information

The dataset contains employee-related information including:

- Age
- Department
- Education
- Job Role
- Monthly Income
- Job Satisfaction
- Work Life Balance
- Years at Company
- Overtime
- Marital Status
- Business Travel
- Performance Rating
- Environment Satisfaction

Target Variable

```
Attrition

Yes → Employee Leaves

No → Employee Stays
```

---

# Project Workflow

```
Business Understanding
        │
        ▼
Data Understanding
        │
        ▼
Exploratory Data Analysis (EDA)
        │
        ▼
Data Cleaning
        │
        ▼
Feature Engineering
        │
        ▼
Encoding
        │
        ▼
Feature Scaling
        │
        ▼
Train-Test Split
        │
        ▼
Model Building
        │
        ▼
Hyperparameter Tuning
        │
        ▼
Model Evaluation
```

---

# Exploratory Data Analysis

Performed detailed EDA to understand employee behavior.

Visualizations include:

- Attrition Distribution
- Monthly Income Distribution
- Job Satisfaction Analysis
- Overtime Analysis
- Years at Company Analysis
- Correlation Heatmap
- Boxplots
- Histograms

Key observations were documented before model building.

---

# Data Preprocessing

The following preprocessing steps were performed:

- Removed unnecessary columns
- Checked missing values
- Checked duplicate records
- One-Hot Encoded categorical features
- Standardized numerical features using StandardScaler
- Split dataset into Training and Testing sets (80:20)

---

# Model

Algorithm Used:

**Logistic Regression**

Why Logistic Regression?

- Simple and interpretable
- Efficient for binary classification
- Produces probability estimates
- Strong baseline model

---

# Hyperparameter Tuning

GridSearchCV was used to determine the optimal hyperparameters.

Parameters tuned included:

- Regularization Strength (C)
- Solver
- Maximum Iterations

The best model was selected based on cross-validation performance.

---

# Model Evaluation

Evaluation metrics used:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Score
- Confusion Matrix

Instead of relying only on Accuracy, multiple evaluation metrics were analyzed to understand model performance on both classes.

---

# Results

The Logistic Regression model demonstrated good overall performance while providing interpretable predictions.

Important takeaway:

High Accuracy alone is **not** sufficient when dealing with classification problems.

Metrics such as Recall, Precision, F1-Score, and ROC-AUC provide a more complete understanding of model quality.

---

# Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook

---

# Repository Structure

```
Employee-Attrition-Logistic-Regression/

│
├── Employee_attrition/
│   ├── train.csv
│   └── test.csv
│
├── images/
│
├── Employee_Attrition_Log_Reg.ipynb
│
├── requirements.txt
│
└── README.md
```

---

# Key Learnings

Through this project I learned:

- End-to-End Machine Learning Workflow
- Binary Classification
- Logistic Regression Mathematics
- Sigmoid Function
- Feature Engineering
- One-Hot Encoding
- StandardScaler
- Hyperparameter Tuning
- Cross Validation
- Model Evaluation
- Business Interpretation of ML Models

---

# Future Improvements

Possible improvements include:

- Random Forest Classifier
- XGBoost Classifier
- LightGBM
- CatBoost
- SMOTE for handling class imbalance
- Feature Selection
- Ensemble Learning

---

# Author

**Mohammed Dhinojwala**

Aspiring AI Engineer

Currently documenting my journey of becoming an AI Engineer through hands-on Machine Learning projects.

GitHub:
(Add your GitHub Profile)

LinkedIn:
(Add your LinkedIn Profile)

---

# If you found this project helpful

Please consider giving this repository a ⭐.

It motivates me to continue building and sharing more Machine Learning projects.
