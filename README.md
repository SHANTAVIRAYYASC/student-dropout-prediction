# Student Dropout and Performance Prediction System

Predicts whether a student is likely to **drop out, stay enrolled, or graduate**
so institutions can identify at-risk students early and support them in time.

## Problem Statement
Student dropout affects institutions and students alike. This project uses
academic, demographic, and socio-economic data to flag high-risk students and
explain the factors behind the prediction.

## Dataset
UCI "Predict Students' Dropout and Academic Success" dataset
(~4,400 students, 36 features, 3 classes: Dropout / Enrolled / Graduate).

## Approach
1. Data cleaning and exploratory data analysis
2. Feature engineering (e.g. curricular unit pass ratio, semester-wise grade change)
3. Model comparison: Logistic Regression, Random Forest, XGBoost
4. Class imbalance handling (class weights / SMOTE)
5. Explainability with SHAP and feature importance
6. Deployment as a Streamlit app

## Tech Stack
Python, pandas, NumPy, scikit-learn, XGBoost, SHAP, Matplotlib, Seaborn, Streamlit

## Results
| Model | Accuracy | Dropout Recall | Macro F1 |
|-------|----------|----------------|----------|
| Baseline Random Forest | TBD | TBD | TBD |

## Project Structure
├── data/
├── notebooks/
├── figures/
├── src/
├── app.py
├── requirements.txt
└── README.md

## How to Run
pip install -r requirements.txt
python day1_eda_baseline.py
streamlit run app.py

## Author
Shantavirayya S C
[LinkedIn](https://linkedin.com/in/shantavirayya-s-1234a) | [GitHub](https://github.com/ShantavirayyaSC)
