Credit Risk Prediction App
Project Overview

This project builds a machine learning model to predict whether a loan applicant represents good or bad credit risk.

The model is trained using historical credit data and deployed using a Streamlit web interface for real-time prediction.

Problem Statement

Financial institutions must assess credit risk before approving loans.

This project predicts credit risk based on applicant attributes such as:

Age

Sex

Job level

Housing status

Saving accounts

Checking account

Credit amount

Loan duration

Model Details

Algorithm: Extra Trees Classifier

Feature encoding applied for categorical variables

Model serialized using joblib

Streamlit Interface

The app allows users to:

Input applicant details

Encode categorical variables automatically

Generate real-time prediction

Display whether credit risk is GOOD or BAD

Tech Stack

Python

Pandas

Scikit-learn

Streamlit

Joblib

How to Run

Clone the repository

Install dependencies

pip install -r requirements.txt


Run the app

streamlit run app/credit_risk_interface.py

Future Improvements

Hyperparameter tuning

Model performance comparison

Add probability scores

Deploy to Streamlit Cloud

Author

Subash Chandra Bose


