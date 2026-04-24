# 📡 Telecom Customer Churn Prediction & Profit Optimization

## 🧠 Business Problem

Customer churn is one of the biggest challenges in the telecom industry, leading to significant revenue loss.  
The goal of this project is not just to predict churn, but to **maximize business profit by optimizing model decisions**.

---

## 🎯 Project Objective

- Predict customers likely to churn  
- Compare multiple machine learning models  
- Optimize decision thresholds  
- Evaluate models based on **business profit**, not just accuracy  

---

## 📊 Dataset Overview

- ~7000 telecom customers  
- Key features:
  - Tenure in Months  
  - Monthly Charges  
  - Total Charges  
  - Contract Type  
  - Unlimited Data  

---

## ⚙️ Machine Learning Models Used

- Logistic Regression  
- Random Forest  
- XGBoost  

Each model was trained and evaluated using classification metrics and business impact.

---

## 📈 Model Evaluation Approach

Instead of relying only on accuracy, the models were evaluated using:

- Recall (Churn Detection)
- Precision
- Profit-Based Evaluation 💰

---

## 🚀 Key Insights

- Logistic Regression, when combined with **threshold tuning**, captured a high number of churn-risk customers.
- Random Forest and XGBoost provided strong overall performance and balance.
- The default threshold (0.5) is not optimal for business goals.

---

## 💰 Business Impact

A custom profit function was implemented to simulate real-world outcomes:

- Correctly identifying churn customers increases retention opportunities  
- Misclassifications were assigned financial impact  

👉 This allows the model to be evaluated based on **profit optimization**, not just technical performance.

---

## 🏆 Final Conclusion

This project demonstrates that:

> The best model is not always the most accurate —  
> but the one that maximizes business value.

By optimizing prediction thresholds and evaluating profit impact, telecom companies can:

- Reduce customer churn  
- Improve retention strategies  
- Increase overall profitability  

---

## 📂 Project Structure
Telecom-Churn-Prediction/
│
├── telecom_churn.ipynb
├── README.md
├── dataset.csv (or external link)


---

## 🛠️ Tools & Libraries

- Python  
- Pandas  
- Scikit-learn  
- XGBoost  
- Matplotlib / Seaborn  

---

## 📌 Future Improvements

- Hyperparameter tuning for XGBoost  
- Deployment as an API  
- Integration with CRM systems for real-time churn prediction  

---

## 👤 Author

**Salim katawazai**  
Telecom Sales Professional | Machine Learning Eng (In Progress)  

---
