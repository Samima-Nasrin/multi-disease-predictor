# Multi-Disease Predictor

A Streamlit-based web app that predicts the likelihood of **Diabetes**, **Parkinson's Disease**, and **Heart Disease** using trained Machine Learning models.

## Features
- Predicts **3 different diseases** from user input data.
- Simple, interactive web UI built with [Streamlit](https://streamlit.io/).
- Uses pre-trained ML models stored locally.
- Trains `Logistic Regression` and `Support Vector Machine` models on an sample dataset to train.
- Runs entirely in your browser — no installation needed for users.

---

## Models
This project uses three separate models:
- `diabetes_model.sav` – predicts Diabetes
- `parkinsons_model.sav` – predicts Parkinson's Disease
- `heart_model.sav` – predicts Heart Disease

Each model was trained with scikit-learn and saved with `pickle`.

---

## Dataset

The dataset used is the **Diabetes Prediction** dataset from Kaggle:  
[[https://www.kaggle.com/datasets/iammustafatz/diabetes-prediction-dataset](https://www.kaggle.com/datasets/iammustafatz/diabetes-prediction-dataset)]

The dataset used is the **Heart Disease Prediction** dataset from Kaggle:  
[[https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset)]

The dataset used is the **Parkinson's Disease Prediction** dataset from Kaggle:  
[[https://www.kaggle.com/datasets/vikasukani/parkinsons-disease-data-set](https://www.kaggle.com/datasets/vikasukani/parkinsons-disease-data-set)]
