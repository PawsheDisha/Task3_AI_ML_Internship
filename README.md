# Task 3: Linear Regression – AI & ML Internship

## Objective

The objective of this task is to implement and understand Simple and Multiple Linear Regression using Python and Scikit-learn. The model is trained to predict house prices based on features such as area, number of bedrooms, and bathrooms.

---

## Tools and Libraries Used

* Python
* Pandas – for data loading and preprocessing
* Matplotlib – for visualization
* Scikit-learn – for building and evaluating the regression model

---

## Dataset

House Price Prediction Dataset (CSV format) containing features like:

* Area
* Bedrooms
* Bathrooms
* Price (Target Variable)

---

## Steps Performed

### 1. Data Import and Preprocessing

* Loaded dataset using Pandas
* Checked for missing values
* Selected relevant features and target variable

### 2. Train-Test Split

* Split dataset into training set (80%) and testing set (20%) using train_test_split

### 3. Model Training

* Used LinearRegression from sklearn.linear_model
* Trained the model on the training data

### 4. Prediction

* Predicted house prices using the test dataset

### 5. Model Evaluation

Evaluated model performance using:

* MAE (Mean Absolute Error) – average prediction error
* MSE (Mean Squared Error) – squared error measure
* R² Score – shows how well the model explains variance

### 6. Visualization

* Plotted Actual vs Predicted values
* Visualized regression performance

### 7. Model Interpretation

* Printed intercept and coefficients
* Interpreted how each feature affects house price

---

## Results

The Linear Regression model successfully learned the relationship between input features and house prices.

* Higher area increases price
* More bedrooms increase price
* More bathrooms increase price
* R² score showed good prediction accuracy

---

## What I Learned

* Difference between Simple and Multiple Linear Regression
* How to train regression models using Scikit-learn
* How to evaluate regression performance using MAE, MSE, and R²
* How to interpret regression coefficients
* How to visualize regression results

---

## Conclusion

Linear Regression is a simple and effective algorithm for predicting continuous values. Multiple Linear Regression improves prediction accuracy by using multiple features. This task helped understand regression modeling, evaluation, and interpretation.

---
