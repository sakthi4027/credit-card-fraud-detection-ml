# credit-card-fraud-detection-ml
credit-card-fraud-detection-ml

# Credit Card Fraud Detection (Machine Learning)

##  Project Overview

This project aims to detect fraudulent credit card transactions using Machine Learning techniques.
Due to the highly imbalanced nature of the dataset, special handling techniques are applied to improve fraud detection performance.

---

## Features

* Data preprocessing and feature scaling
* Handling imbalanced data using **SMOTE**
* Model training using **Random Forest Classifier**
* Evaluation using **Precision, Recall, and F1-score**

---

## Dataset

The dataset used in this project is publicly available on Kaggle:
https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

* Total transactions: 284,807
* Fraud cases: 492
* Highly imbalanced dataset

---

## Tech Stack

* Python
* Pandas
* Scikit-learn
* Imbalanced-learn (SMOTE)

---

## Project Workflow

1. Load dataset
2. Data preprocessing (scaling + cleaning)
3. Train-test split (with stratification)
4. Handle imbalance using SMOTE
5. Train Random Forest model
6. Evaluate model performance

---

## Results

* Precision (Fraud): **0.95**
* Recall (Fraud): **0.82**
* F1-score: **0.88**

> Note: Accuracy is not a reliable metric due to class imbalance.

---

##  Key Insights

* The model achieves high precision, meaning most detected fraud cases are correct.
* Recall is improved using SMOTE, ensuring more fraud cases are identified.
* Balancing precision and recall is critical in fraud detection systems.

---

##  How to Run

1. Download the dataset from Kaggle
2. Place `creditcard.csv` in the project folder
3. Run the Python script or Jupyter Notebook

---

##  Author
**Sakthivel**
Aspiring AI Developer 

---

## ⭐ Future Improvements

* Improve recall using threshold tuning
* Try advanced models like XGBoost
* Build a Streamlit web application
