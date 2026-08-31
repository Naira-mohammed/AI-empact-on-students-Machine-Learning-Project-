# AI-empact-on-students-Machine-Learning-Project-
# 🎓 Impact of AI on Students: Student Burnout Risk Prediction

An end-to-end Machine Learning pipeline designed to analyze student data, evaluate behavioral patterns related to AI usage, and predict student burnout risk levels. The project encompasses a complete ML lifecycle—from rigorous Exploratory Data Analysis (EDA) and feature engineering to model interpretability and deployment.

---

## 📌 Project Overview
As artificial intelligence increasingly integrates into educational environments, understanding its psychological and academic impact on students is crucial. This project builds a robust classification system to identify students at high risk of academic burnout, enabling timely interventions and support.

---

## 🚀 Project Roadmap & Workflow
Our development process follows a strict 21-step data science lifecycle tracked via GitHub Projects:

1. **Problem Definition & Target Identification** (#1)
2. **Data Understanding & Column Mapping** (#2)
3. **Data Cleaning & Quality Check** (#3)
4. **Exploratory Data Analysis (EDA)** (#4)
5. **Outlier Analysis & Treatment** (#5)
6. **Train/Test Stratified Split** (#6)
7. **Feature Engineering** (#7)
8. **Preprocessing (Encoding & Scaling)** (#8)
9. **Feature Selection** (#9)
10. **Baseline Model Implementation** (#10)
11. **Classification Models Exploration** (#11)
12. **Cross-Validation (Stratified K-Fold)** (#12)
13. **Class Imbalance Handling** (#13)
14. **Hyperparameter Tuning** (#14)
15. **Model Evaluation & Comparison** (#15 - Focus on High Burnout Class)
16. **Model Explainability (SHAP / Feature Importance)** (#16)
17. **Error Analysis** (#17)
18. **Final Model & End-to-End Pipeline** (#18)
19. **Final Testing on Unseen Data** (#19)
20. **Advanced ML / Ensembling** (#20)
21. **Deployment** (#21)

---

## 🛠️ Tech Stack & Libraries
* **Language:** Python
* **Data Manipulation & Analysis:** Pandas, NumPy
* **Visualization:** Matplotlib, Seaborn
* **Machine Learning:** Scikit-Learn, XGBoost, LightGBM
* **Interpretability:** SHAP
* **Deployment:** Streamlit, Joblib

---

## 📂 Repository Structure
```text
├── data/               # Raw and processed datasets
├── notebooks/          # Google Colab / Jupyter notebooks for steps execution
├── src/                # Python scripts for pipeline, training, and deployment
├── models/             # Saved model binaries (.pkl / .joblib)
├── requirements.txt    # Project dependencies
└── README.md           # Project documentation
