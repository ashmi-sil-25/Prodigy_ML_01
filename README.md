# **HOUSE PRICE PREDICTION USING LINEAR REGRESSION** #

### 1. Import Necessary Libraries ###
- `pandas` for data handling
- `numpy` for numerical operations
- `matplotlib.pyplot` (though not used in the script)
- `sklearn` for model training and evaluation

### 2. Load the Dataset ###
- Reads house price data from a CSV file using pd.read_csv().

### 3. Define Features (X) and Target Variable (y) ###
- Features: `area`, `bedrooms`, `bathrooms`
- Target: `price`

### 4. Split the Data into Training and Testing Sets ###
- Uses `train_test_split()` (80% training, 20% testing).

### 5. Train a Linear Regression Model ###
- Uses `LinearRegression()` from `sklearn` to fit the training data.

### 6. Make Predictions ###
- Predicts house prices for `x_test`.

### 7. Evaluate Model Performance ###
- Uses **Mean Absolute Error (MAE), Mean Squared Error (MSE)**, and R² Score to measure accuracy.

### 8. Predict New House Price ###
- Makes a prediction for a house with **3000 sq. ft area, 2 bedrooms, and 1 bathroom.**

## Key Objective: ##
To develop a **Linear Regression model** that accurately predicts **house prices** based on **square footage, number of bedrooms, and number of bathrooms**, using **machine learning techniques** to analyze housing data and provide reliable price estimations.
  
