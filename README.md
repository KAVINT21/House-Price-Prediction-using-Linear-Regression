# House-Price-Prediction-using-Linear-Regression

# Dependencies

1.pandas
2.numpy
3.matplotlib
4.scikit-learn
5.gradio

# Overview
This project is a simple yet effective implementation of house price prediction using machine learning. The goal is to predict the price of a house based on various features such as location, total square feet area, number of bathrooms, and number of bedrooms (BHK).

# Project Components

# 1. Data Cleaning and Outlier Removal
The initial step involves cleaning the dataset and removing outliers to ensure the model's robustness. The remove_pps_outliers function is used to filter out instances where the price per square foot deviates significantly from the mean for a specific location.

# 2. Data Visualization
To understand the data distribution, a scatter plot is created using the plot_scatter_chart function. This function visualizes the price distribution for 2 BHK and 3 BHK houses in a given location.

![Screenshot 2024-01-24 095336](https://github.com/KAVINT21/House-Price-Prediction-using-Linear-Regression/assets/95117554/ac156711-b901-460e-988d-4fb6951a8235)

![Screenshot 2024-01-24 095455](https://github.com/KAVINT21/House-Price-Prediction-using-Linear-Regression/assets/95117554/a9b11772-741c-4986-b62e-ca0c9733ab6e)

# 3. Machine Learning Model

A linear regression model is employed to predict house prices. The model is trained using the scikit-learn library.

![Screenshot 2024-01-24 095729](https://github.com/KAVINT21/House-Price-Prediction-using-Linear-Regression/assets/95117554/f225149d-3bd4-4390-8f45-06f1edd3f644)

# 4. Gradio Interface for Prediction
Gradio is utilized to create a user-friendly interface for predicting house prices. The predict_price function takes inputs such as location, square feet area, number of bathrooms, and number of bedrooms, and provides the predicted house price.

![Screenshot 2024-01-24 094655](https://github.com/KAVINT21/House-Price-Prediction-using-Linear-Regression/assets/95117554/84209d5e-a2ef-4c1e-bc13-1ff704cca32e)
