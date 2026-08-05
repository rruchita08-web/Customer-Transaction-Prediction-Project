Built an end-to-end Customer Transaction Prediction system using Python and Scikit-learn on the Santander dataset. Includes EDA, preprocessing, Logistic Regression, Decision Tree, Random Forest, Gradient Boosting, hyperparameter tuning, cross-validation, feature importance, and evaluation using Accuracy, Precision, Recall, F1-score, and ROC-AUC.

# 💳 Customer Transaction Prediction using Machine Learning

<p align="center">

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?logo=scikitlearn)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-013243?logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-blue)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Plots-4C72B0)
![Google Colab](https://img.shields.io/badge/Google-Colab-F9AB00?logo=googlecolab)
![GitHub](https://img.shields.io/badge/GitHub-Repository-black?logo=github)

</p>

---

## 📌 Project Overview

This project develops an **end-to-end Machine Learning solution** to predict whether a customer will perform a future banking transaction using the **Santander Customer Transaction Prediction** dataset.

The project follows an **industry-standard machine learning workflow**, covering business understanding, exploratory data analysis (EDA), preprocessing, model building, hyperparameter tuning, cross-validation, feature importance analysis, and business insights.

The objective is to help financial institutions improve customer targeting and support data-driven decision-making.

---

# 🎯 Business Problem

Banks collect vast amounts of customer data, but identifying customers who are likely to perform future transactions remains a challenge.

By building a predictive machine learning model, banks can:

- Improve targeted marketing campaigns
- Increase conversion rates
- Reduce marketing costs
- Improve customer engagement
- Support data-driven business decisions

---

# 📊 Dataset Information

| Attribute | Details |
|------------|---------|
| Dataset | Santander Customer Transaction Prediction |
| Source | Kaggle |
| Rows | 200,000 |
| Columns | 202 |
| Features | 200 Numerical Features |
| Target Variable | `target` |
| Identifier | `ID_code` |

---

# 🔄 Project Workflow

```text
Business Understanding
        │
        ▼
Data Understanding
        │
        ▼
Exploratory Data Analysis
        │
        ▼
Data Preprocessing
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
Cross Validation
        │
        ▼
Feature Importance
        │
        ▼
Business Insights
        │
        ▼
Final Model
```

---

# 🛠 Technologies Used

| Category | Technologies |
|----------|--------------|
| Programming Language | Python |
| Notebook | Google Colab |
| Data Analysis | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Machine Learning | Scikit-learn |
| Version Control | Git & GitHub |

---

# 🤖 Machine Learning Models

The following classification algorithms were implemented and compared:

- ✅ Logistic Regression
- ✅ Decision Tree Classifier
- ✅ Random Forest Classifier
- ✅ Gradient Boosting Classifier

The best-performing model was further optimized using **GridSearchCV**.

---

# 📈 Model Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC Score
- Confusion Matrix
- Cross Validation

---

# 📷 Project Screenshots

## 📊 Correlation Heatmap

> Save your heatmap inside **images/** folder.

```markdown
![Correlation Heatmap](images/correlation_heatmap.png)
```

---

## 🌳 Feature Importance

```markdown
![Feature Importance](images/feature_importance.png)
```

---

## 📈 ROC Curve

```markdown
![ROC Curve](images/roc_curve.png)
```

---

## 📉 Confusion Matrix

```markdown
![Confusion Matrix](images/confusion_matrix.png)
```

---

# 📌 Key Features

✔ Business Understanding

✔ Comprehensive Exploratory Data Analysis (EDA)

✔ Missing Value Analysis

✔ Duplicate Data Analysis

✔ Outlier Detection

✔ Data Preprocessing

✔ Feature Scaling

✔ Multiple Machine Learning Models

✔ Hyperparameter Tuning

✔ Cross Validation

✔ Feature Importance Analysis

✔ Business Insights

✔ Challenges & Limitations

✔ Future Improvements

---

# 📂 Repository Structure

```text
Customer-Transaction-Prediction-Project
│
├── Customer_Transaction_Prediction_project.ipynb
├── README.md
├── requirements.txt
├── LICENSE
├── .gitignore
└── images/
    ├── correlation_heatmap.png
    ├── feature_importance.png
    ├── roc_curve.png
    └── confusion_matrix.png
```

---

# 🚀 How to Run

1. Clone this repository

```bash
git clone https://github.com/rruchita08-web/Customer-Transaction-Prediction-Project.git
```

2. Install dependencies

```bash
pip install -r requirements.txt
```

3. Open the notebook

```bash
jupyter notebook
```

or upload the notebook to **Google Colab**.

---

# 🔮 Future Improvements

- Implement XGBoost, LightGBM, and CatBoost
- Apply SMOTE for class imbalance handling
- Perform advanced feature engineering
- Deploy the model using Streamlit or Flask
- Monitor model drift in production

---

# 👩‍💻 Author

**Ruchita Davager**

📧 Email: *Add your email here*

🔗 GitHub: https://github.com/rruchita08-web

---

# ⭐ If you found this project helpful, consider giving it a Star!

