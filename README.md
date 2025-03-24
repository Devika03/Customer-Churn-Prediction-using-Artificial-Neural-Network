
---

# Customer Churn Prediction using Artificial Neural Network

## Overview

This project involves building an Artificial Neural Network (ANN) for predicting Customer Churn. The dataset used contains various customer attributes, and the ANN is trained to predict whether a customer is likely to exit the bank.

https://github.com/user-attachments/assets/73e12104-91e8-4940-a8b0-820c8dd6190d

## Files

- **Churn_Modelling.csv**: Dataset used for training and testing the ANN.
- **app.py**: Streamlit-based Web-app for deploying the machine learning model, allowing users to input features and receive predictions .
- **Experiments.ipynb**: Jupyter Notebook containing the code for data preprocessing, model building, training, and evaluation .
- **label_encoder_gender.pkl** , **onehot_encoder_geo.pkl** , **scaler.pkl**: Pickle Files of Encoders & Scalers . 
- **model.h5**: Pre-trained model stored in HDF5 format .
- **Prediction.ipynb**: Jupyter Notebook for loading the trained .pkl and .h5 models and making predictions.

## Results

- **Accuracy**: The trained model achieves an accuracy of approximately 86.5% on the test set.
