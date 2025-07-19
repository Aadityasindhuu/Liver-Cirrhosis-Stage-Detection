
---
title: Liver Cirrhosis Stage Prediction
emoji: 🩺
colorFrom: blue
colorTo: indigo
sdk: streamlit
sdk_version: 1.22.0
app_file: app.py
pinned: false
---

# Liver Cirrhosis Stage Prediction App

This app predicts the histologic stage of liver disease (1, 2, or 3) based on clinical and laboratory data from the Mayo Clinic PBC study.

## Features
- Predicts liver cirrhosis stage (1-3)
- Shows prediction probabilities
- Clean, user-friendly interface
- Deployed using Streamlit

## How to Use
1. Enter patient clinical data in the form
2. Click "Predict Stage"
3. View results and interpretation

## Model Details
- Algorithm: XGBoost Classifier
- Training Data: Mayo Clinic PBC study
- Metrics: Accuracy > 95% (based on the notebook evaluation)

*Note: This tool is for research purposes only and should not replace professional medical advice.*
