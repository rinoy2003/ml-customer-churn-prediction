# ml-customer-churn-prediction
Customer Churn Prediction using Machine Learning with EDA, model optimization, and business insights


## 📌 Problem Statement
Customer churn is a major challenge in the telecom industry. 
Losing customers directly impacts revenue and growth.

This project aims to predict whether a customer will churn using machine learning, 
so businesses can take proactive steps to retain customers.

---

## 📊 Dataset Information
- Total Records: 7043 customers  
- Features: Demographics, account details, services  
- Target Variable: Churn (Yes/No)

---

## 🔍 Project Workflow

1. Data Cleaning  
2. Exploratory Data Analysis (EDA)  
3. Data Preprocessing  
4. Model Building  
5. Model Evaluation  
6. Model Improvement  
7. Business Insights  

---

## 📈 Exploratory Data Analysis

Key findings from EDA:

- Customers with **high monthly charges** are more likely to churn  
- Customers with **low tenure** have higher churn probability  
- **Month-to-month contracts** show higher churn  

---

## 🤖 Models Used

- Logistic Regression  
- Random Forest  
- Support Vector Machine (SVM)  

---

## ⚙️ Model Improvement

To improve performance:

- Applied **Hyperparameter Tuning (GridSearchCV)**  
- Focused on **Recall instead of Accuracy**  
- Used **Threshold Tuning (0.5 → 0.3)**  

📌 Why Recall?  
Missing a churn customer is more costly than a false prediction.

---

## 📊 Results

- Accuracy: ~79%  
- Recall (Churn): Improved from **48% → 75%**  
- AUC Score: **0.82**  

---
## 📊 Visualizations

### ROC Curve
![ROC](roc_curve.png)

## 💡 Business Insights

- High-paying customers are at risk of churn  
- Short-term customers are more likely to leave  
- Flexible contracts increase churn probability  

### 📌 Recommendations:
- Offer long-term plans  
- Improve customer support  
- Provide targeted retention offers  

---

## 🏁 Conclusion

The model successfully predicts customer churn with strong performance.

By focusing on recall, the model ensures better identification of potential churn customers, 
making it useful for real-world business applications.

---

## 🛠️ Technologies Used

- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  

---

## 📂 Project Structure

- Notebook: Model and analysis  
- Dataset: Customer data  
- README: Project documentation  

---

## ⭐ Key Highlight

This project focuses on **real-world decision making**, prioritizing recall 
to minimize business loss due to customer churn.
