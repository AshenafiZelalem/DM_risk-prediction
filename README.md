🩺 Diabetes Risk Prediction — Machine Learning Project

Overview

This project develops and evaluates multiple machine learning models to predict early-stage diabetes risk based on symptom and demographic data.  
Using a dataset of 520 patient records, the notebook explores data preprocessing, exploratory data analysis (EDA), feature encoding, and predictive modeling with five classifiers and an optimized ensemble.

Methods
Algorithms used:
- Logistic Regression  
- Random Forest  
- XGBoost  
- Support Vector Machine (SVM)  
- Multilayer Perceptron (Neural Network)  
- Bayesian-Optimized Ensemble Model  

Key tasks:
- Data cleaning and transformation  
- Feature encoding and scaling  
- Model training and evaluation  
- Comparative visualization of accuracy, F1, and ROC-AUC  
- Ensemble tuning via Bayesian optimization

📊 Results
Model Performance Summary					

<img width="512" height="161" alt="image" src="https://github.com/user-attachments/assets/3ab12fe4-0a6c-4b1a-8ae2-253a1afc07b6" />


Best model: Support Vector Machine (SVM)  
Interpretation: The models show high discriminative power; symptoms such as *polyuria*, *polydipsia*, and *sudden weight loss* are key predictors.

💡 Next Steps
- Validate model on real-world Ethiopian patient data.
- Implement SHAP for explainability.
- Deploy as an interactive prediction dashboard (Streamlit/Power BI).

🧩 Tech Stack
Python, scikit-learn, XGBoost, seaborn, matplotlib, Bayesian Optimization, Jupyter/Colab

## 🧑‍⚕️ Author
**Dr. Ashenafi [MD, MPH, Healthcare Data Scientist]**  
*Merging Clinical and public health with data science for actionable healthcare intelligence.*
