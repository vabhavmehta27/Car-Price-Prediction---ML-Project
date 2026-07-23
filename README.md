# Car Price Prediction using Machine Learning
A Machine Learning project that predicts the selling price of used cars based on various vehicle attributes. 
The project performs complete data preprocessing, feature engineering, model comparison, and prediction using multiple regression algorithms.

# Project Overview

Buying or selling a used car requires estimating its fair market value. 
This project uses Machine Learning techniques to predict the selling price of a car based on features such as:
- Present Price
- Kilometers Driven
- Fuel Type
- Seller Type
- Transmission
- Number of Previous Owners
- Age of Vehicle

The project compares multiple regression models and selects the best-performing model for prediction.

# Features
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Null Value Checking
- Data Preprocessing
- Feature Engineering
- Outlier Removal
- Categorical Data Encoding
- Train-Test Split
- Multiple Machine Learning Models
- Model Performance Comparison
- Model Saving using Joblib
- New Car Price Prediction
- Simple Prediction GUI using ipywidgets

# Dataset
The dataset contains information about used cars including:
- Car Name
- Year
- Selling Price (Target)
- Present Price
- Kilometers Driven
- Fuel Type
- Seller Type
- Transmission
- Owner

Additional Feature Created:
- Vehicle Age

# Technologies Used
- Python
- Google Colab
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Joblib
- ipywidgets

# Machine Learning Models Used
- Linear Regression
- Random Forest Regressor
- Gradient Boosting Regressor
- XGBoost Regressor

# Project Workflow
1. Import Libraries
2. Load Dataset
3. Data Exploration
4. Check Missing Values
5. Data Preprocessing
6. Feature Engineering
7. Outlier Removal
8. Encode Categorical Variables
9. Train-Test Split
10. Train Multiple Models
11. Evaluate Performance
12. Save Best Model
13. Predict Car Price
14. GUI Prediction Interface

# Output
The project predicts the estimated selling price of a used car based on user inputs.

Example Inputs:
- Present Price = 5.59
- Kilometers Driven = 27000
- Fuel Type = Petrol
- Seller Type = Dealer
- Transmission = Manual
- Owner = 0
- Age = 8

Predicted Selling Price:
3.48 Lakhs (Approx.)
