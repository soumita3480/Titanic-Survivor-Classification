# Titanic-Survivor-Classification
Titanic Survival Prediction 🛳️
Overview
This project implements a binary classification model that predicts whether a passenger survived the Titanic disaster, based on features like age, gender, ticket class, fare, etc. The goal is to demonstrate a full open‑source ML pipeline—including data preprocessing, feature engineering, model training & evaluation, and explainability.

🧠 Data & Problem Statement
Dataset: Kaggle's “Titanic – Machine Learning from Disaster” dataset, containing passenger information and whether they survived 
Prediction Task: Classify passengers as Survived = 1 or 0 based on input features.

Data Processing & Feature Engineering
Cleaning & handling missing values: Impute missing Age (i.e., mean) and drop high-missing features like Cabin because of excessive nulls

Model Development & Evaluation
Algorithms Tried: Logistic Regression, Naive Bayes
Training & Validation: Used an 80/20 train/test split
Metrics: Model comparison based on accuracy, precision, recall, F1-score,Confusion.
