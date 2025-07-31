# Tuberculosis-Detector: A Machine Learning-Based Tuberculosis Prediction System
Overview
This project presents a machine learning-based system for predicting tuberculosis (TB) using clinical and demographic data. The aim is to develop a tool that enables fast, accessible, and reliable TB detection, particularly for resource-limited regions with high TB prevalence.
The project was originally conceptualized during my undergraduate studies, where I led its design, feature engineering, model training, evaluation, and web deployment using Flask. The version presented here has been independently developed and enhanced by me for demonstration purposes.

Objectives
Predict TB infection using supervised machine learning.
Compare multiple classification models and select the best based on accuracy and recall.
Provide a user-friendly interface via a Flask web application.
Serve as a low-cost diagnostic aid in high-burden regions.

Technologies Used
Python, Pandas, Scikit-learn
SVM, Logistic Regression, Decision Tree Classifier
Flask for web deployment
HTML/CSS for the front-end
Joblib for model serialization

How It Works
Data Preprocessing: Handles missing data, encodes categorical features, and performs feature engineering (e.g., age binning, interaction features).
Model Training: Trains multiple classifiers with cross-validation and evaluates them using accuracy, precision, recall, and ROC-AUC.
Model Deployment: Saves the best-performing model (SVM) and integrates it with a Flask-based front-end for real-time predictions.

Results
The Support Vector Machine (SVM) model was selected based on its superior recall and ROC-AUC score, ensuring fewer false negatives.
Flask app allows users (patients or healthcare workers) to input test data and get instant predictions.

 Impact & Relevance
This project is especially relevant for the SADC region, where TB remains a public health crisis. It aligns with the broader goal of improving diagnostic accessibility through AI in developing countries.

Author
Palesa Emily Thetele
Final Year BSc (Hons) Computing
thetelepalesa406@gmail.com 



