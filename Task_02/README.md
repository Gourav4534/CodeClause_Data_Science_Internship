## Customer Lifetime Value Prediction
### Overview
This repository contains a data science project focused on predicting the lifetime value of customers for a business based on their historical interactions. The project aims to apply regression techniques to estimate the future value that a customer will bring to the business. Python and various libraries such as Pandas, NumPy, Matplotlib, Seaborn, and Scikit-learn are utilized for this project.

## Project Structure
Data Loading and Exploration: The dataset (Online Retail.xlsx) is loaded into a Pandas DataFrame. Initial exploration is conducted to understand the structure and characteristics of the data.

Data Preprocessing: Preprocessing steps include converting the type of the Invoice Date field from string to datetime and creating additional fields for analysis.

Customer Segmentation: Customer segmentation is performed based on Recency, Frequency, and Revenue (RFM) scores using K-means clustering. This step helps in identifying different customer segments.

LTV Calculation: Customer Lifetime Value (LTV) is calculated using revenue data and further analysis is conducted to understand the distribution of LTV across different customer segments.

Model Building:

K-means Clustering: K-means clustering is applied to segment customers into Low LTV, Mid LTV, and High LTV clusters.
XGBoost Classifier: An XGBoost classifier is trained to predict the LTV clusters based on customer features.

Model Evaluation: The trained XGBoost classifier is evaluated on training and test sets to assess its performance using accuracy metrics.
