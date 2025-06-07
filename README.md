# 💳 Credit Card Fraud Detection

This project tackles the problem of **credit card fraud detection** using anonymized transaction data and **machine learning techniques**. Due to the highly imbalanced nature of fraud datasets, special attention is given to class balancing using **SMOTE**.

---

## 📁 Dataset

- Source: [Kaggle Credit Card Fraud Detection](https://www.kaggle.com/mlg-ulb/creditcardfraud)
- 284,807 transactions, with only 492 fraud cases.
- Features: 30 anonymized features (`V1` to `V28` from PCA), `Amount`, `Time`, and target label `Class`.

---

## 🔧 What This Project Covers

1. **Data Cleaning & Preprocessing**
   - Scaling of numeric features
   - Dropping non-numeric columns
2. **Exploratory Data Analysis (EDA)**
   - Distribution of legitimate vs. fraudulent transactions
3. **Imbalanced Data Handling**
   - Using **SMOTE** to generate synthetic fraud examples
4. **Model Training**
   - Trained with **Random Forest Classifier**
   - Evaluated with:
     - Confusion matrix
     - Classification report
     - ROC-AUC curve
     - Precision-Recall (PR) curve
5. **Threshold Tuning**
   - Custom probability threshold to boost **recall**
6. **Final Evaluation**
   - Tested on **original imbalanced dataset**
   - Achieved high performance:
     - `ROC AUC score`: **0.998**
     - `Recall`: Improved via threshold tuning

---

## 📈 Results

- The model correctly identifies fraudulent transactions with high accuracy.
- Thanks to SMOTE and ROC tuning, **recall and precision are both optimized**.

---

## 📊 Visuals Included

- ROC Curve
- PR Curve
- Confusion Matrix
- Class distribution (before & after SMOTE)
![download](https://github.com/user-attachments/assets/9a43a7ea-d62c-47b5-971c-e2bd3edeab34)


---

👤 Author
Pierre Musili
📧 Email: pierremusili@gmail.com
🔗 LinkedIn: linkedin.com/in/pierre-musili


