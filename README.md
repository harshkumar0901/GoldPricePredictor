Gold Price Prediction using Random Forest Regressor
Overview
This project builds a machine learning model to predict gold prices using a Random Forest Regressor. The notebook performs data preprocessing, exploratory data analysis (EDA), feature correlation analysis, model training, and evaluation.
The project uses historical financial indicators such as:
SPX (S&P 500 Index)
USO (United States Oil Fund)
SLV (Silver prices)
EUR/USD exchange rate


The target variable is:
GLD — Gold price

Dataset
The dataset used in this project is:
gld_price_data.csv

Features
Feature	Description
SPX	S&P 500 Index
USO	Oil prices
SLV	Silver prices
EUR/USD	Euro to USD exchange rate
GLD	Gold price (Target Variable)
Technologies Used
Python
NumPy
Pandas
Matplotlib
Seaborn
Scikit-learn


Machine Learning Algorithm
The project uses:
Random Forest Regressor
Random Forest is an ensemble learning algorithm that combines multiple decision trees to improve prediction accuracy and reduce overfitting.

Advantages
Handles nonlinear relationships
Reduces overfitting
Works well on tabular datasets
Provides strong predictive performance


How to Run the Project
1. Clone the Repository : 
   git clone https://github.com/harshkumar0901/GoldPricePredictor
2. Install Dependencies : 
   pip install numpy pandas matplotlib seaborn scikit-learn
3. Run the Notebook : 
   jupyter notebook gold.ipynb
