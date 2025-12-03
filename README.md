
# 📉 Customer Churn Prediction Using Machine Learning | End-to-End Python Project

In this project, we develop a machine learning model to **predict customer churn** using real-world Telcom dataset. This end-to-end project walks through the entire ML pipeline — from **data preprocessing** and **feature engineering** to **model training**, **evaluation**, and **business recommendations**.

---

## 🚀 Project Overview

Customer churn is a critical metric for any business, especially in banking, telecom, and subscription-based services. The goal of this project is to identify patterns that predict whether a customer is likely to churn (leave) — helping businesses proactively improve **customer retention**.

---

## 🧠 What You’ll Learn

✅ How to clean and preprocess structured customer data  
✅ How to perform EDA (Exploratory Data Analysis) to uncover insights  
✅ Engineering powerful features like **Balance**, **Tenure**, and **Product Usage**  
✅ Building and comparing ML models like **Logistic Regression**, **Random Forest**, and **XGBoost**  
✅ Evaluating models using metrics like **Accuracy**, **Precision**, **Recall**, **F1-Score**, and **ROC-AUC**  
✅ Visualizing trends in churn behavior with **Seaborn** and **Matplotlib**  
✅ Using insights for **data-driven customer retention strategies**

---

## 🧩 Tools & Libraries Used

- **Python**
- **Pandas**, **NumPy** – Data processing
- **Matplotlib**, **Seaborn** – Data visualization
- **Scikit-learn** – Model training & evaluation
- **XGBoost** – Advanced gradient boosting model
- **Joblib** – Model saving
- **Warnings**, **Collections** – Utility libraries

---

## 🔍 Steps Performed

### 1. 📥 Data Import & Inspection
- Loaded dataset using `pandas`
- Checked data shape, types, missing values, and target variable distribution

### 2. 🔎 Exploratory Data Analysis (EDA)
- Analyzed churn distribution across categorical and numerical variables
- Explored relationships between:
  - **Churn vs. Age**
  - **Churn vs. Balance**
  - **Churn vs. Tenure**
  - **Churn vs. Product Usage**
- Plotted histograms, box plots, and bar plots

### 3. 🧼 Data Cleaning & Preprocessing
- Handled missing values
- Scaled numerical features using `StandardScaler` or `MinMaxScaler`
- Encoded categorical variables using:
  - `OneHotEncoder` for nominal variables
  - `LabelEncoder` where appropriate
- Split data into **train-test** sets

### 4. 🏗 Feature Engineering
- Engineered features such as:
  - Account balance
  - Number of products used
  - Duration of customer tenure
  - Interaction terms (e.g., balance per tenure)

### 5. 🤖 Model Training & Tuning
- Trained several models:
  - Logistic Regression
  - Random Forest
  - XGBoost
  - Naive Bayes
  - Gradient Boosting
- Used cross-validation and grid search for hyperparameter tuning

### 6. 📊 Model Evaluation
- Evaluated each model using:
  - **Accuracy**
  - **Precision**
  - **Recall**
  - **F1-Score**
  - **ROC-AUC**
- Plotted confusion matrices and ROC curves

### 7. 💾 Model Saving
- Best-performing model was saved using `joblib` for deployment or reuse

---

## 📈 Key Insights

- Customers with **high account balances** but **low tenure** showed higher churn rates
- **Product usage** was a significant predictor of churn
- **XGBoost** model achieved the highest performance across all evaluation metrics

---

## 💡 Business Recommendations

- Monitor and engage high-balance, short-tenure customers early
- Incentivize long-term engagement via loyalty programs
- Use churn prediction scores to prioritize customer service resources
- Launch retention campaigns targeting high-risk segments

---

## 📣 Get in Touch

If you're working on customer analytics, churn modeling, or predictive data science — let's connect! I'm always open to collaboration and sharing knowledge.
