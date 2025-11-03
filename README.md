# Telco Customer Churn Model Comparison

## 📊 Project Overview
This notebook predicts customer churn using the **Telco Customer Churn Dataset**. It compares Logistic Regression, SVM, and Random Forest models on metrics like accuracy, precision, recall, and ROC-AUC, followed by cross-validation using StratifiedKFold.

---

## ⚙️ Steps Performed
1. **Data Loading & Exploration**
   - Loaded and inspected the dataset
   - Cleaned missing and inconsistent data

2. **Data Visualization**
   - Visualized churn distribution and correlations using matplotlib & seaborn

3. **Preprocessing**
   - Encoded categorical features
   - Scaled numeric data with StandardScaler
   - Performed train-test split

4. **Model Training**
   - Trained Logistic Regression, SVM, and Random Forest models

5. **Model Evaluation**
   - Compared models using Accuracy, Precision, Recall, Confusion Matrix, and ROC-AUC
   - Logistic Regression achieved the best overall performance

6. **Cross Validation**
   - Used StratifiedKFold (5 folds) for robust performance estimation

---

## 🧮 Key Metrics for Model Comparison
For churn prediction, **ROC-AUC** and **Recall** are most important:
- **ROC-AUC:** Measures the model’s ability to distinguish churners from non-churners
- **Recall:** Captures how many actual churners were correctly identified

---

## 🧰 Technologies Used
- Python (Jupyter Notebook)
- pandas, numpy
- matplotlib, seaborn
- scikit-learn

---

## 📈 Results Summary

| Model | Accuracy | ROC-AUC | Recall | Comment |
|--------|-----------|---------|----------|----------|
| Logistic Regression | 0.82 | 0.86 | 0.58 | Best performing overall |
| SVM | 0.81 | 0.85 | 0.54 | Good but slightly lower |
| Random Forest | 0.80 | 0.84 | 0.48 | Worst Performing |

---

## 📬 Author
**Mehar Singh Bawa**  
