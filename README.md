# Credit Card Fraud Detection using Machine Learning

This project focuses on detecting fraudulent credit card transactions using **Logistic Regression**. It is a real-world classification problem where the dataset is highly imbalanced.

---

##  Objective

The goal of this project is to build a machine learning model that can accurately classify transactions as:

- ✅ Legitimate (0)
- ❌ Fraudulent (1)

---

##  Dataset

- Dataset: Credit Card Fraud Detection Dataset  
- Source: Kaggle  
- Contains anonymized features (V1, V2, ..., V28), Amount, and Class

---

##  Key Challenge

The dataset is highly imbalanced:

- Majority class (Normal transactions)
- Minority class (Fraud transactions)

Handling this imbalance is a crucial part of the project.

---

##  Project Workflow

1. Load Dataset  
2. Data Understanding (EDA)  
3. Remove Duplicates  
4. Feature Scaling (Amount column)  
5. Handle Imbalanced Data (Resampling)  
6. Train-Test Split  
7. Model Training (Logistic Regression)  
8. Prediction  
9. Model Evaluation  

---

## Data Preprocessing

- Removed duplicate records  
- Scaled the `Amount` feature using StandardScaler  
- Handled class imbalance using resampling technique  

---

## Model Used

- Logistic Regression

---

## Evaluation Metrics

- Accuracy  
- Confusion Matrix  
- Precision  
- Recall  
- F1 Score  

> Note: In fraud detection, **Precision and Recall** are more important than accuracy.

---

## Key Learnings

- Importance of data preprocessing in ML  
- Handling imbalanced datasets  
- Real-world application of classification models  
- Why evaluation metrics matter  

---

## Results

(Add your graphs/screenshots here)

---

## 🔗 GitHub Repository

(Add your repo link here)

---

## Technologies Used

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib / Seaborn  

---

## Future Improvements

- Use SMOTE for better balancing  
- Try advanced models (Random Forest, XGBoost)  
- Improve feature engineering  

---

##  Conclusion

This project demonstrates how machine learning can be applied to detect fraud in financial transactions and highlights the importance of proper data preprocessing.

---

If you like this project, feel free to star the repository!
