# Diabetes Prediction (Hybrid: Clinical + ML)

This project builds and deploys a machine learning model for predicting diabetes using clinical indicators and symptoms such as FPG, HbA1c, BMI, Weight Loss, Nocturia, Polyuria, Age, and Gender.
The model is trained using Random Forest/XGBoost and deployed with Gradio for an interactive user interface.

## 🚀 Features
- Preprocessing with **SMOTE** to balance dataset
- Models trained: Logistic Regression, Random Forest, XGBoost
- Deployment using **Gradio**
- Hybrid decision system (Clinical + ML)

## 📊 Results
- Random Forest achieved **99% accuracy** and **ROC-AUC ~0.999**
- HbA1c and FPG are most influential features

## 🛠️ How to Run
```bash
# Install dependencies
pip install -r requirements.txt

# Run app
python app/app.py
