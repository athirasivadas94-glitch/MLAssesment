# MLAssesment
# Car Price Prediction Using Machine Learning

## Project Overview

This project aims to analyze the factors that influence car prices in the American automobile market. A Chinese automobile company planning to enter the US market wants to understand how different car features affect pricing.

Using machine learning techniques, regression models were built to predict car prices based on various vehicle attributes.

---

## Dataset

The dataset contains information about different cars and their features such as engine size, horsepower, fuel type, and mileage.

Dataset link:
https://drive.google.com/file/d/1FHmYNLs9v0Enc-UExEMpitOFGsWvB2dP/view

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## Project Steps

### 1. Data Loading and Preprocessing

* Loaded the dataset
* Checked for missing values and duplicates
* Performed encoding of categorical variables
* Checked skewness and outliers
* Feature scaling and train-test split

### 2. Model Implementation

The following regression algorithms were implemented:

* Linear Regression
* Decision Tree Regressor
* Random Forest Regressor
* Gradient Boosting Regressor
* Support Vector Regressor

---

### 3. Model Evaluation

The models were evaluated using:

* R² Score
* Mean Squared Error (MSE)
* Mean Absolute Error (MAE)

| Model             | R² Score  |
| ----------------- | --------- |
| Linear Regression | 0.881     |
| Decision Tree     | 0.861     |
| Random Forest     | **0.947** |
| Gradient Boosting | 0.935     |
| SVR               | 0.850     |

Random Forest Regressor achieved the best performance.

---

### 4. Feature Importance

Feature importance analysis showed that the most influential variables affecting car price are:

* Curb Weight
* Engine Size
* Highway MPG
* Horsepower
* Brand

---

### 5. Hyperparameter Tuning

Hyperparameter tuning was performed using GridSearchCV to optimize the Random Forest model. The tuned model achieved similar performance, confirming that the model was already well optimized.

---

## Conclusion

The Random Forest Regressor provided the best performance for predicting car prices. The results indicate that factors such as engine size, vehicle weight, fuel efficiency, and horsepower significantly influence car pricing in the American market.

This model can help automobile companies understand pricing dynamics and design vehicles that match market demands.

---

