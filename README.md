# nigeria-houses-price-prediction
This project predicts house prices in Nigeria using Linear Regression and XGBoost models. The dataset includes features like bedrooms, bathrooms, toilets, parking spaces, house type, town, state, and price. The code preprocesses the data, trains the models, and evaluates their performance.

##Project Overview
Goal: Predict house prices in Nigeria.
Dataset: nigeria_houses_data.csv (not included; provide your own).
Models: Linear Regression and XGBoost.
Features: Numerical (e.g., bedrooms) and categorical (e.g., town, state).
Preprocessing: Feature engineering, scaling, encoding, log transformation.
Dataset
Columns: bedrooms, bathrooms, toilets, parking_space, title, town, state, price.
Size: 24,326 entries.
Source: User-provided CSV (e.g., /content/drive/MyDrive/nigeria_houses_data.csv).
Requirements
Python 3.7+
Libraries: numpy, pandas, matplotlib, seaborn, scikit-learn, category_encoders, xgboost

##Results
Linear Regression
MAE (NGN): 0.43 (likely a bug; expected in millions).
R² (log scale): 0.6500.
R² (original scale): 0.6586.
Top Features: town, state_Plateau.
XGBoost
MAE (NGN): 53,851,020.25.
R² (log scale): 0.7136.
R² (original scale): 0.7138.
Top Features: title_Detached Duplex, town.
XGBoost outperforms Linear Regression in R², but MAE suggests room for improvement.
