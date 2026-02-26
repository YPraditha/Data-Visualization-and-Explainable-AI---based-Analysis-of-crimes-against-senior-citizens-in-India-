🧠 Crimes Against Senior Citizens — Data Visualization & Explainable AI

This project analyzes NCRB data on crimes against senior citizens in India using Data Visualization and Explainable Artificial Intelligence (XAI). It builds a neural network model to study conviction patterns and explains predictions using SHAP and LIME.

🚀 Features

State-wise crime analysis

Police & court disposal efficiency study

Neural Network regression model

SHAP for global feature importance

LIME for state-level explanation

Clear and interpretable AI-based insights

📂 Dataset

NCRB Crime Against Senior Citizens (Chapter 6A)

Police Disposal Data

Court Disposal Data

Cleaned and structured CSV datasets

🧠 Model

Multi-Layer Perceptron (MLPRegressor)

Predicts Conviction Rate (%)

Evaluated using MAE and R² score

🔍 Explainability

SHAP identifies globally important factors affecting conviction rate.

LIME explains why a specific state has a high or low predicted conviction rate.

📊 Insights

Higher chargesheeting improves conviction outcomes.

High pendency and acquittals reduce efficiency.

Judicial performance indicators strongly influence conviction rates.

▶️ Usage

Run the notebook:

senior_citizen_analysis.ipynb

Install dependencies:

pip install shap lime scikit-learn pandas matplotlib seaborn
👩‍💻 Author

Praditha
MSc Data Science
Mini Capstone Project
