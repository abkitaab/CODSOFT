Credit Card Fraud Detection

## Overview
This project detects fraudulent credit card transactions using **Machine Learning** techniques. The models used include:

- **Logistic Regression**  
- **Random Forest Classifier**  
- **XGBoost Classifier**

The dataset is highly imbalanced, so techniques like **SMOTE** are applied to balance the training data. The project includes data preprocessing, model training, evaluation, and visualization of results.

---

## Dataset
- The dataset used is [Credit Card Fraud Detection Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud) from Kaggle.
- Features include anonymized transaction details (V1, V2, ..., V28), `Amount`, and `Class` (0 = Genuine, 1 = Fraud).  

---

## Features
- `Time` – Seconds elapsed between each transaction and the first transaction in the dataset  
- `V1` to `V28` – Anonymized numerical features derived from PCA  
- `Amount` – Transaction amount  
- `Class` – Target variable (0 = genuine, 1 = fraud)  

---

## Author

Your Name
Data Science Intern – CODSOFT
