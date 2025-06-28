# Customer Subscription Prediction with Decision Trees

This project analyzes the **Bank Marketing Dataset**  to predict whether a client will subscribe to a term deposit. It involves data preprocessing, feature engineering, model building with a Decision Tree, and performance evaluation.

---

## Problem Statement

The dataset contains information about a direct marketing campaign of a Portuguese bank. The goal is to develop a machine learning model that can predict if a customer will subscribe to a term deposit based on demographic and historical data.

---

##  Objective

- Perform Exploratory Data Analysis (EDA)
- Encode categorical features and scale numerical ones
- Build and train a Decision Tree Classifier
- Apply feature selection and hyperparameter tuning
- Evaluate model performance using various metrics

---

## Dataset

- Source: [UCI Bank Marketing Dataset](https://archive.ics.uci.edu/ml/datasets/bank+marketing)
- Records: 45,211
- Features: 17 (including categorical and numerical)

---

##  Techniques Used

- Label Encoding
- Standardization using StandardScaler
- Feature selection with RandomForest
- Hyperparameter tuning using GridSearchCV
- Evaluation: Accuracy, Confusion Matrix, Classification Report

---

#  Results

-  **Training Accuracy**: 0.8975  
-  **Testing Accuracy**:  0.8984

---

##  Conclusion

The Decision Tree Classifier provided interpretable and accurate predictions on customer subscription behavior. The model highlights the most influential factors and serves as a valuable tool for marketing targeting. Further improvement could involve ensemble models like Random Forest or XGBoost.

---


## Tools & Libraries

- Python
- Pandas, Matplotlib, Seaborn
- Scikit-learn

