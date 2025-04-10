# Retention Radar 🔍👩‍💼

Retention Radar is a predictive analytics project that helps organizations identify which employees are at risk of leaving. By analyzing key features from employee data, the model provides retention insights that can guide HR decisions and improve workforce stability.

## 🚀 Features

- Predicts whether an employee is likely to stay or leave
- Analyzes key factors like satisfaction, evaluation, workload, etc.
- Helps HR teams proactively address attrition
- Clean and interactive interface (optional: add if you have one)
- Supports data visualization for insights

## 🧠 Technologies Used

- Python
- Scikit-learn / XGBoost / TensorFlow (update based on your model)
- Pandas, NumPy
- Matplotlib / Seaborn for data visualization
- Streamlit / Flask (if web app is included)
- Jupyter Notebook for exploration

## 📊 Dataset

We use an HR dataset containing the following attributes (customize as needed):

- Employee satisfaction level
- Last evaluation score
- Number of projects
- Average monthly hours
- Time spent at the company
- Work accident
- Promotion in last 5 years
- Department
- Salary level
- Retention label (0 = stayed, 1 = left)

## 🔍 Model Overview

The project involves:

1. **Data Cleaning & Preprocessing** – Handling missing values, encoding categorical features.
2. **Feature Selection** – Identifying key factors influencing retention.
3. **Model Training** – Using machine learning algorithms to predict retention.
4. **Evaluation** – Accuracy, precision, recall, F1-score.
5. **Deployment** – (optional) Web interface to upload and analyze new data.

## 📈 Sample Results

Example accuracy: **89%**

Confusion Matrix, ROC Curve, and other evaluation metrics are used for validation.

## 💡 Future Improvements

- Add explainability (e.g., SHAP values)
- Integrate with HR dashboards
- Continuous learning with real-time feedback

