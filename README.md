# LOAN_PREDICT
# Loan Prediction using Machine Learning

## Project Overview

This project aims to predict whether a loan applicant is likely to default on a loan based on demographic, financial, and loan-related attributes. Various machine learning classification algorithms were implemented, evaluated, and compared to identify the best-performing model.

---

## Objective

The objective of this project is to build and compare multiple machine learning models for loan default prediction and evaluate their performance using standard classification metrics.

---

## 📂 Dataset

The dataset contains information about loan applicants, including:

* Age
* Income
* Education
* Employment Status
* Credit Score
* Loan Amount
* Loan Purpose
* Loan Term
* Number of Dependents
* Marital Status
* Mortgage Status
* Property Area
* Previous Defaults
* Loan Default (Target Variable)

---

## 🛠️ Data Preprocessing

The following preprocessing steps were performed:

* Removed unnecessary columns
* Checked for missing values
* Encoded binary categorical variables
* Applied One-Hot Encoding to categorical features
* Split the dataset into training and testing sets
* Applied feature scaling where appropriate

---

## 🤖 Machine Learning Models

The following classification algorithms were implemented:

* Logistic Regression
* Decision Tree Classifier
* Random Forest Classifier
* K-Nearest Neighbors (KNN)
* XGBoost Classifier

---

## 📊 Evaluation Metrics

The models were evaluated using:

* Accuracy
* Confusion Matrix
* Classification Report
* ROC-AUC Score

Feature importance was also analyzed for tree-based models.

---

## Results

All models were trained and compared based on their performance.

The **Random Forest Classifier** achieved the best overall performance with an accuracy of approximately **88.46%** on the test dataset.

---

## Libraries Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* XGBoost

---

## Future Improvements

* Hyperparameter tuning
* Cross-validation
* Precision-Recall Curve
* Model deployment using Flask or Streamlit
* Handling class imbalance using techniques such as SMOTE

---

## Conclusion

This project demonstrates the complete machine learning workflow, including data preprocessing, feature engineering, model training, evaluation, and comparison. Among the implemented models, Random Forest provided the best predictive performance for this dataset.

---

## 👩‍💻 Author

**Divya Chaudhary**

Machine Learning | Data Science | Python
