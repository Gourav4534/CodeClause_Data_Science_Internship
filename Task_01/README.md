## House Price Prediction Project

### Overview
This repository contains a data science project focused on predicting house prices using machine learning techniques. The project employs Python and various libraries such as Pandas, NumPy, Matplotlib, Seaborn, and Scikit-learn. The goal is to build and compare two regression models: a simple linear regression model and a random forest regression model.

### Project Structure
Data Loading and Exploration: The dataset (House Price India.csv) is loaded into a Pandas DataFrame. Initial exploration is conducted to understand the structure and characteristics of the data.

Data Preprocessing: Preprocessing steps include handling missing values, converting data types, removing unnecessary columns, and standardizing features.

Exploratory Data Analysis (EDA): EDA is performed to visualize relationships between independent variables and the target variable (house prices). This step aids in identifying important features and understanding correlations.

Principal Component Analysis (PCA): PCA is applied to reduce the dimensionality of the dataset while retaining most of the variance. This enhances model performance and efficiency.

Model Building:

Linear Regression Model: A simple linear regression model is trained using Scikit-learn to predict house prices based on selected features.
Random Forest Regression Model: A random forest regression model is also trained to compare its performance with the linear regression model.

Model Evaluation: The performance of both models is evaluated using metrics such as Mean Squared Error (MSE), Mean Absolute Error (MAE), and R-squared (R2).
