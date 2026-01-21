# Predictive-Data-Mining-Drug-Prediction-
Predictive Data Mining: Drug Recommendation System
Predictive Data Mining: Drug Recommendation System
Project Overview

This project builds a predictive model to recommend the most suitable drug for a patient based on medical attributes such as age, sex, blood pressure, cholesterol level, and sodium-to-potassium ratio.

Dataset

The dataset contains patient health records with:

Age, Sex

Blood Pressure (BP)

Cholesterol

Na_to_K ratio

Target variable: Prescribed Drug (A, B, C, X, Y)

Methodology

A Decision Tree Classifier was used to learn decision rules from historical patient data.

Steps:

Data cleaning and encoding of categorical variables

Train-test split

Hyperparameter tuning (max_depth, max_leaf_nodes, max_features)

Model evaluation using MAE, MSE, and R²

Final model selection and visualization

Interactive drug prediction function

Results

Best model achieved very high accuracy (R² ≈ 0.98)

Decision tree clearly shows how medical factors influence drug selection

An interactive system predicts drugs for new patient inputs

Tools & Technologies

Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Google Colab

Outcome

This project demonstrates how predictive data mining and decision tree models can support healthcare decision-making and serve as a foundation for AI-based clinical recommendation systems.
