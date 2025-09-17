# Diabetes Prediction (Hybrid: Clinical + ML)

This project predicts diabetes using both **clinical rules** (WHO thresholds for HbA1c and FPG) and a **machine learning model (Random Forest)** trained on patient data.

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
