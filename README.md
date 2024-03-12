# Telecom Churn Prediction Model

## Overview
This repository contains a deep learning model for predicting whether customers of a telecom company churn (stop using the product). The model is trained on a dataset containing various customer features such as monthly charges, tenure, gender, and total charges, among others. The goal is to predict whether a customer will churn (leave the service) based on these features utilizing TensorFlow and Keras.

## PART 1: Get and Clean the Telecom Customer Churn Data
We created an ETL (Extract, Transform, Load) pipeline which contains code to acquire and clean telecom customer churn data. The dataset is preprocessed to remove missing values, encode categorical variables, and prepare it for training the prediction model.

## PART 2: Split Data into Variables and Features and Train and Test Sets
Once the data is cleaned, it is split into independent variables (features) and dependent variables (target). The dataset is further divided into training and testing sets to train and evaluate the model.

## PART 3: Create Tuner To Find Optimal Neural Network Construction for Neural Network Model
To optimize the neural network model architecture, Keras Tuner is used to search for the best combination of hyperparameters. This step helps in determining the optimal number of layers, neurons, and activation functions for the model.

## PART 4: Create and Validate Deep Learning Model Based on Recommendations from Tuner
Based on the recommendations from the tuner, a deep learning model is created using TensorFlow and Keras. The model architecture is defined and trained using the training dataset. The model is then evaluated for accuracy using the test dataset.

## Requirements
- Python 3.x
- TensorFlow
- Keras Tuner
- Pandas
- Scikit-learn

## Contributors 
* Karl Schultz (github.com/karl-schultz)
* Jamie Kawaguchi (github.com/JamieKawaguchi)
* Andres Erasto (github.com/AndresE99)
* Aiden Tariku (github.com/aidentariku)
* Ali Lakhani (Instructor)
