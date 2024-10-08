# OIBSIP_05

Overview
This project focuses on predicting sales based on various advertising factors such as expenditures on TV, radio, and newspapers. By leveraging machine learning algorithms, this tool aims to help businesses understand how different marketing strategies can influence their sales performance.

Features
Data Collection: Utilizes a dataset containing information on advertising expenditures and corresponding sales figures.
Data Preprocessing: Cleans and preprocesses the dataset for better analysis.
Machine Learning Model: Implements regression algorithms (e.g., Linear Regression) to predict sales based on advertising inputs.
Evaluation Metrics: Assesses model performance using metrics like Mean Squared Error (MSE) and R-squared.
Visualization: Provides graphical insights into the relationship between advertising spend and sales performance.
Dataset
The dataset used in this project contains the following columns:

TV: Advertising budget allocated to TV (in thousands of dollars).
Radio: Advertising budget allocated to radio (in thousands of dollars).
Newspaper: Advertising budget allocated to newspapers (in thousands of dollars).
Sales: Sales figures generated (in thousands of dollars).
You can download the dataset from this link.

Installation
To get started, clone the repository and install the necessary dependencies:

git clone https://github.com/yourusername/sales-prediction.git
cd sales-prediction
pip install -r requirements.txt

Usage
To use the sales prediction model, run the following command in your terminal:
python sales_prediction.py

Model Evaluation
The model's performance is evaluated using various metrics such as:

Mean Squared Error (MSE): Measures the average of the squares of the errors.
R-squared: Indicates how well the independent variables explain the variance in the dependent variable.
