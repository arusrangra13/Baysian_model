# AI---based-E-learning-recommendation-system
Heart Disease Prediction using Bayesian Network

Project Overview
This project implements a Heart Disease Prediction System using a Bayesian Network model.
The goal is to predict the probability of heart disease based on patient health parameters
such as age, blood pressure, cholesterol level, chest pain type, and gender.

Unlike traditional machine learning models, this project uses a probabilistic approach,
making the predictions more interpretable and suitable for medical decision support.

Why Bayesian Network?
- Handles uncertainty in medical data
- Provides probability-based predictions
- Shows cause-and-effect relationships
- More interpretable than black-box ML models

Technologies Used
- Python
- Google Colab
- Pandas
- pgmpy (Bayesian Network library)
- Scikit-learn (optional preprocessing)

Dataset Description
The dataset contains medical attributes related to heart disease, including:
- age : Age of the patient
- sex : Gender (1 = Male, 0 = Female)
- cp : Chest pain type
- trestbps : Resting blood pressure
- chol : Serum cholesterol
- fbs : Fasting blood sugar
- target : Heart disease (1 = Yes, 0 = No)

Continuous values such as age, blood pressure, and cholesterol are converted into
categorical ranges (low, medium, high) for Bayesian Network modeling.

Bayesian Network Structure
The model is designed with the following relationships:
- Age influences Resting Blood Pressure
- Resting Blood Pressure influences Heart Disease
- Cholesterol influences Heart Disease
- Chest Pain influences Heart Disease
- Sex influences Heart Disease

This structure reflects basic medical reasoning and improves model explainability.

How to Run the Project
1. Open Google Colab
2. Upload the dataset file (heart_database.csv)
3. Install required library using:
   pip install pgmpy
4. Run the notebook cells step by step
5. Provide patient details as evidence to get heart disease probability

Sample Prediction Output
Heart Disease = Yes : 0.77
Heart Disease = No  : 0.23

This indicates a 77 percent probability that the patient has heart disease.

Key Features
- Probabilistic heart disease prediction
- Explainable Bayesian model
- Beginner-friendly implementation
- Suitable for academic and college projects

Future Enhancements
- Add more medical features such as ECG, BMI, smoking status
- Compare Bayesian Network with Logistic Regression
- Deploy as a web application
- Save predictions to Google Sheets
- Improve structure using medical expert knowledge

Conclusion
This project demonstrates the use of Bayesian Networks for heart disease prediction.
The probabilistic and explainable nature of the model makes it suitable for healthcare
applications and academic learning.

Author
Heart Disease Prediction Project
Bayesian Network Model
