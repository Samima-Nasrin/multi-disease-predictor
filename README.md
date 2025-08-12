# Multi-Disease Predictor

A Streamlit-based web app that predicts the likelihood of **Diabetes**, **Parkinson's Disease**, and **Heart Disease** using trained Machine Learning models.

## Features
- Predicts **3 different diseases** from user input data.
- Simple, interactive web UI built with [Streamlit](https://streamlit.io/).
- Uses pre-trained ML models stored locally.
- Runs entirely in your browser — no installation needed for users.

## Models
This project uses three separate models:
- `diabetes_model.sav` – predicts Diabetes
- `parkinsons_model.sav` – predicts Parkinson's Disease
- `heart_model.sav` – predicts Heart Disease

Each model was trained with scikit-learn and saved with `pickle`.
