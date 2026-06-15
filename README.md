# credit-card-fraud-detection-using-Machine-Learning-models

# Fraud Detection Pipeline  
## End-to-End Machine Learning Workflow

---

## Project Overview
This project is a complete Fraud Detection Machine Learning Pipeline built to identify fraudulent credit card transactions using real-world imbalanced data.

It includes data preprocessing, class balancing, feature selection, multiple machine learning models, explainability techniques, and deployment using Streamlit.

---

## 1. Data Collection
- Credit Card Transaction Dataset
- Highly imbalanced dataset (fraud vs legitimate transactions)
- Target variable: Fraud (1) vs Legitimate (0)

---

## 2. Data Preprocessing
- Handling missing values
- Feature scaling using StandardScaler
- Removal of irrelevant or redundant features

---

## 3. Class Balancing
- Applied SMOTE (Synthetic Minority Oversampling Technique)
- Balanced minority (fraud) and majority classes
- Improved model learning on rare fraud cases

---

## 4. Feature Selection
- Selected top 17 important features
- Reduced noise and improved model performance
- Focused on most impactful variables

---

## 5. Model Training

### CART (Decision Tree)
- Simple and interpretable model
- Easy to understand decision rules

### Random Forest
- Ensemble of decision trees
- More stable and accurate predictions

### XGBoost
- Gradient boosting model
- High performance on structured data

---

## 6. Model Evaluation
Models were evaluated using:
- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC Score
- Confusion Matrix analysis

---

## 7. Explainable AI (XAI)
- SHAP (SHapley Additive exPlanations): Global feature importance
- LIME (Local Interpretable Model-agnostic Explanations): Local prediction explanation

These techniques help understand why a transaction is classified as fraud or not.

---

## 8. Deployment
- Built using Streamlit
- Interactive web-based dashboard
- Real-time fraud prediction system
- User-friendly machine learning interface

---

## Tech Stack
- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Imbalanced-learn (SMOTE)
- SHAP
- LIME
- Streamlit

---

## Key Highlights
- End-to-end machine learning pipeline
- Handles imbalanced dataset effectively
- Multiple model comparison
- Explainable AI integration
- Deployed interactive dashboard

---

## Author
Aswini Ambati

---

## License
This project is for educational and learning purposes only.
