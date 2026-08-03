# Heart-Disease-Prediction

This repository contains code for a machine learning model that predicts the likelihood of heart disease based on various health-related features. The model is built using logistic regression and is implemented as an interactive web application using Streamlit. The app allows users to input their health information and receive a prediction regarding the presence or absence of heart disease.



## Dataset 📊:
The dataset used in this project is stored in a CSV file named `heartdisease.csv`. It contains several features related to individuals' health, such as age, sex, chest pain type, blood pressure, serum cholestoral, fasting blood sugar, resting electrocardiographic results, maximum heart rate achieved, exercise-induced angina, ST depression induced by exercise, slope of the peak exercise ST segment, number of major vessels colored by fluoroscopy, and thalassemia type. Any missing values in the dataset are removed before training the model.

## Dependencies 🔧:
To run this code, you need the following dependencies:

Python 3.x

NumPy

pandas

scikit-learn

Streamlit

You can install the required packages using the following command:
`pip install numpy pandas scikit-learn streamlit`

## Model Training and Evaluation 📈:
The model is trained using logistic regression, and the dataset is split into training and testing sets using the `train_test_split` function from scikit-learn. The model's accuracy is evaluated using the R-squared metric and displayed on the web application.







