# Heart Failure Prediction using Logistic Regression

This machine learning project predicts the risk of death due to heart failure using clinical patient data and logistic regression.


# Problem Statement

Early prediction of heart failure risk can save lives. Using patient health metrics (like ejection fraction, creatinine, serum sodium), this model predicts the probability of death based on historical records.


# Dataset

- Source: [UCI Heart Failure Clinical Records](https://archive.ics.uci.edu/ml/datasets/Heart+failure+clinical+records)
- Records: 299 patients
- Target: DEATH_EVENT (0 = survived, 1 = died)
- Features: 13 health indicators like age, blood pressure, ejection fraction, time, creatinine level, etc.


# Data Cleaning & Preprocessing

- No missing values
- All features are numerical
- Applied `StandardScaler` to normalize the features
- Performed `train_test_split` (80% train, 20% test)


# Model

- Algorithm: Logistic Regression (Binary Classification)
- Framework: Scikit-learn
- Evaluation Metrics:
  - Accuracy Score
  - Confusion Matrix
  - Classification Report (Precision, Recall, F1)
  - Feature Importance


# Results

| Metric     | Value       |
|------------|-------------|
| Accuracy   | ~75–85%     |
| Precision  | Shown in report |
| Important Features | Ejection Fraction, Serum Creatinine, Time |


#  Visualization

- ✅ Feature importance bar chart
- ✅ Confusion matrix heatmap


#Tools & Libraries

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn


# Author

Abhishek Darsan H  
AI & Data Science Learner | Python & ML Enthusiast  
[LinkedIn](https://www.linkedin.com/in/abhishek-darsan-h-551399274)

# Future Work

- Try Random Forest, XGBoost for better performance
- Add patient-level interpretability (e.g., SHAP values)
- Build a Streamlit app for doctors to input values and predict risk



