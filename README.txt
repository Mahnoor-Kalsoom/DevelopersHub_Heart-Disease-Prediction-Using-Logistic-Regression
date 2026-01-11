# ❤️ Heart Disease Prediction Using Logistic Regression  
*(DevelopersHub – Task 2)*

## 📌 Objective  
The objective of this task is to build a machine learning model that predicts whether a person is at risk of heart disease based on medical and health-related attributes.  
This task demonstrates the complete workflow of a **binary classification problem** using **Logistic Regression**.

This task is part of the **AI/ML Engineering Internship** at **DevelopersHub Corporation**.

---

## 📊 Dataset  
- **Dataset Name:** Heart Disease Dataset  
- **File:** `heart.csv`  
- **Source:** UCI Machine Learning Repository / Kaggle  
- **Description:**  
  The dataset contains medical and clinical attributes such as:
  - Age  
  - Sex  
  - Chest pain type  
  - Resting blood pressure  
  - Cholesterol level  
  - Fasting blood sugar  
  - Maximum heart rate  
  - Exercise-induced angina  
  - And other health indicators  

The target variable indicates:
- `0` → No heart disease  
- `1` → Presence of heart disease  

---

## 🧹 Data Preprocessing  
The following preprocessing steps were applied:

- Loaded the dataset using **Pandas**
- Handled missing values:
  - Numerical features filled using median
  - Categorical features filled using mode
- Dropped irrelevant or unnecessary columns (if any)
- Encoded categorical variables using **One-Hot Encoding**
- Split the dataset into:
  - Training set  
  - Testing set  
- Scaled numerical features using **StandardScaler**

---

## 🤖 Model Used  

- **Algorithm:** Logistic Regression  
- **Reason:**  
  Logistic Regression is a powerful and interpretable algorithm for binary classification problems, especially in healthcare applications where understanding predictions is important.

---

## 📈 Model Evaluation  

The model performance was evaluated using:

- ✅ **Accuracy Score**
- 📊 **Confusion Matrix**
- 📑 **Classification Report**
  - Precision  
  - Recall  
  - F1-score  
- 📉 **ROC Curve & AUC Score**

These metrics help in understanding:
- How well the model predicts heart disease  
- The balance between false positives and false negatives  
- Overall model reliability  

---

## 🔍 Feature Importance  

Feature importance was analyzed using the coefficients of the Logistic Regression model to determine which medical attributes had the most impact on predicting heart disease.  
This provides insight into:
- Key health risk factors  
- Model interpretability  

---

## 🛠 Technologies Used  

- Python 3.x  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- Jupyter Notebook  

---

## 🎯 Learning Outcomes  

- Built a complete ML pipeline:
  - Data loading  
  - Cleaning & preprocessing  
  - Model training  
  - Evaluation  
- Gained hands-on experience with:
  - Logistic Regression  
  - Feature scaling  
  - Model interpretation  
- Improved understanding of healthcare-related machine learning problems  

---

## ✅ Conclusion  

This project demonstrates a complete and structured approach to solving a real-world classification problem using **Logistic Regression**.  
The achieved results show that Logistic Regression is an effective baseline model for heart disease prediction and can support early medical risk assessment.

---

## 👩‍💻 Author  

**Name:** Mahnoor Kalsoom  
**Task:** AI/ML Internship – Task 2  
**Organization:** DevelopersHub Corporation  
