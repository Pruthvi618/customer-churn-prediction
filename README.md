# 📊 Customer Churn Prediction

## 🎯 Objective

Predict whether a customer will churn using machine learning techniques.

## 💼 Business Problem

Customer churn leads to revenue loss. This project helps identify at-risk customers so businesses can take preventive actions.

---

## 📂 Dataset

* Customer demographics and service usage
* Target: **Churn (Yes/No)**

---

## 🛠️ Tech Stack

* Python
* Pandas, NumPy
* Scikit-learn
* Matplotlib, Seaborn

---

## ⚙️ Approach

1. Data Cleaning
2. Exploratory Data Analysis (EDA)
3. Feature Engineering
4. Model Building (Logistic Regression)
5. Model Evaluation
6. Threshold Tuning

---

## 📈 Results

* Accuracy: ~78%
* Recall improved from **47% → 75%** using threshold tuning
* Best Threshold: **0.3**

---

## 🔥 Key Insights

* Customers with **low tenure** are more likely to churn
* **Month-to-month contracts** have highest churn
* **Higher monthly charges** increase churn probability
* **Electronic check users** show higher churn

---

## 🚀 Future Improvements

* Try Random Forest / XGBoost
* Handle imbalance using SMOTE
* Hyperparameter tuning
* Deploy using Streamlit

---

## 📌 How to Run

```bash
pip install -r requirements.txt
python customer_churn_prediction_using_logistic_regression.py
```

---

## 👨‍💻 Author

Pruthvi
