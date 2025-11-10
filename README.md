# 🧠 Insurance Customer Churn Prediction App

This project aims to predict whether an insurance customer is likely to **churn** (leave the company) based on their profile, claims history, policy type, and satisfaction level.  
The goal is to help insurance companies **identify at-risk customers early** and take proactive steps to retain them.

---

## 📁 Project Structure


---

## 🚀 Features

- Exploratory Data Analysis (EDA) and cleaning
- Feature encoding and scaling
- Model training using:
  - Logistic Regression  
  - Decision Tree  
  - Random Forest  
  - Support Vector Machine (SVM)
- Evaluation using accuracy, precision, recall, and F1-score
- Handling class imbalance with class weights
- Model persistence using `joblib`
- Deployment-ready Streamlit app (coming soon)

---

## 📊 Dataset Overview

The dataset contains information about insurance policyholders, such as:

- **Demographic info** (age, gender, location)
- **Policy details** (type, start/end date, premium)
- **Claims info** (total claims, amount, last claim date)
- **Customer satisfaction and contact frequency**
- **Churn status** (whether the customer left)

---

## 🧮 Model Performance (Initial Results)

| Model | Accuracy | Precision | Recall | F1 Score |
|--------|-----------|------------|----------|-----------|
| Logistic Regression | 1.00 | 1.00 | 1.00 | 1.00 |
| Decision Tree | 1.00 | 1.00 | 1.00 | 1.00 |
| Random Forest | 1.00 | 1.00 | 1.00 | 1.00 |
| Support Vector Machine | 0.70 | 0.20 | 0.11 | 0.14 |

> These are preliminary results. The next step is to retrain models using scaled features and perform 5-fold cross-validation.

---

## ⚙️ Next Steps

1. Scale numerical features and retrain SVM.
2. Perform 5-fold cross-validation on all models.
3. Save the best model using `joblib`.
4. Build and deploy the **Streamlit web app**.
5. Add visual explanations (feature importance, SHAP values).

---

## 🧰 Tech Stack

- **Python** (Pandas, NumPy, Scikit-learn, Matplotlib)
- **Google Colab** (Model training)
- **Reflex** (App interface)
- **Joblib** (Model saving/loading)
- **GitHub** (Version control)

---

## 👨‍💻 Author

**Ali** — Machine Learning Engineer  
*Passionate about AI solutions for business and healthcare.*

---
