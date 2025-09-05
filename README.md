# 📊 Customer Churn Prediction

## 📌 Project Overview
This project explores **customer churn prediction** using two machine learning models:  
- Logistic Regression  
- Random Forest  

The goal is to evaluate which model performs better at predicting churn.  

During the project, I discovered that the dataset suffers from **class imbalance**, which negatively impacts model performance. While neither model achieved strong predictive power, the **Random Forest classifier performed slightly better** in terms of accuracy.  

---

## 🔎 Methodology
1. **Data Preprocessing**
   - Handled missing values
   - Encoded categorical features
   - Split data into train/test sets

2. **Exploratory Data Analysis (EDA)**
   - Customer demographics
   - Churn distribution (revealed imbalance in target)

3. **Modeling**
   - Logistic Regression  
   - Random Forest  

4. **Evaluation**
   - Accuracy, Precision, Recall, F1-score  
   - Confusion Matrix
   - Classification Reports

---

## 📊 Results
- **Logistic Regression:** struggled due to imbalance  
- **Random Forest:** achieved higher accuracy, but still limited by imbalance  

👉 Key Insight: Handling **class imbalance** (e.g., using SMOTE, class weights, or resampling) would likely improve performance.  

---

## 🛠️ Tech Stack
- Python (Pandas, Scikit-learn, Seaborn)  
- Jupyter Notebook  

---

## 📌 Next Steps
- Apply **resampling techniques** (SMOTE, undersampling, oversampling)  
- Tune Random Forest hyperparameters  
- Explore alternative models (XGBoost, Gradient Boosting)  

---

## 👩‍💻 Author
**Raudhotul Jannah**  

