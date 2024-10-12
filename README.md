# ANN-Classification-Churn

# Customer Churn Prediction Web App

## Project Overview

This project is a web application built using **Streamlit** and **TensorFlow** for predicting customer churn. The prediction model is a **deep learning** model, specifically an artificial neural network (ANN), trained on the **Churn Modelling** dataset. The app allows users to input customer data, such as credit score, age, and account balance, and predicts the probability of whether the customer will churn or not.

## Features

- **Real-time Predictions:** The web app allows users to input customer details and instantly receive churn probability predictions.
- **Deep Learning Model:** The core model is a deep learning Artificial Neural Network (ANN) designed to predict customer churn based on input features.
- **Interactive UI:** Built with **Streamlit**, the app provides an easy-to-use interface for users to input customer data and view the prediction results.

## Dataset

The dataset used for this project is the **Churn_Modelling.csv**, which contains 10,000 records of customer data from a bank. Each record includes the following features:

- **Credit Score**
- **Geography**
- **Gender**
- **Age**
- **Tenure**
- **Balance**
- **Number of Products**
- **Has Credit Card**
- **Is Active Member**
- **Estimated Salary**
- **Exited (Target variable)**

## Deep Learning Model Overview

The deep learning model (ANN) has the following architecture:

1. **Input Layer:** Receives 12 features after preprocessing.
2. **Hidden Layers:** 
   - First hidden layer with 65 neurons and ReLU activation.
   - Second hidden layer with 32 neurons and ReLU activation.
3. **Output Layer:** 
   - Single neuron with sigmoid activation for binary classification (churn or no churn).

The model is compiled using the **Adam** optimizer and **binary cross-entropy** as the loss function. Accuracy is used as the evaluation metric.

