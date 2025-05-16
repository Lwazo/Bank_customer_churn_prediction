# 🏦 Bank Customer Churn Prediction

This project uses machine learning to predict whether a customer will leave a bank (churn). By analyzing customer behavior and financial data, the model helps banks take proactive steps to retain valuable clients.

---

## 🎯 Objective

To build a predictive model that classifies customers as **likely to churn** or **stay**, using historical customer data.

---

## 🛠️ Tools & Technologies

- Python  
- Pandas, NumPy – Data handling  
- Seaborn, Matplotlib – Visualization  
- Scikit-learn – Machine Learning & Evaluation  
- Random Forest Classifier – Final Model

---

## 📊 Dataset Summary

The dataset contains data of over 10,000 bank customers with features such as:

- Credit Score  
- Geography  
- Gender  
- Age  
- Tenure  
- Balance  
- Number of Products  
- Has Credit Card  
- Is Active Member  
- Estimated Salary  

Target variable:  
- **Exited**: 1 = churned, 0 = stayed

---

## 📈 Approach

1. **Data Preprocessing**  
   - Dropped irrelevant columns (e.g., CustomerId, Surname)  
   - Encoded categorical features (Gender, Geography)  
   - Applied feature scaling with `StandardScaler`

2. **Model Training**  
   - Split data: 80% training / 20% testing  
   - Trained a `RandomForestClassifier` on scaled features  
   - Evaluated with classification metrics and ROC-AUC score  

3. **Model Evaluation**  
   - Accuracy, Precision, Recall, F1-score  
   - Confusion Matrix and ROC Curve  
   - Feature importance plot

---

## ✅ Key Results

- Model performed well with strong classification metrics
- Top features influencing churn included:
  - Age
  - Balance
  - Geography
  - IsActiveMember
  - Number of Products

---

## 💼 Business Value

- Enables banks to **identify at-risk customers**  
- Supports **targeted marketing and retention campaigns**  
- Reduces churn rate, improving **customer lifetime value**

---

## 📦 Future Enhancements

- Deploy as an interactive web app with **Streamlit**  
- Add real-time input for new customer predictions  
- Try advanced models (e.g., XGBoost, CatBoost)

---

## 📁 Files

- `churn_prediction.ipynb` – Main notebook with code  
- `README.md` – Project summary  
- `Churn_Modelling.csv` – Dataset used  

---

## 👤 Author

**Lwazoluhle Mhlongo**  
Aspiring Data Scientist | Passionate about Banking & AI
