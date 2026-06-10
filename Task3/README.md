# Model Validation, Overfitting Control & Hyperparameter Tuning

## Project Overview

This project focuses on improving machine learning model performance through model validation, overfitting detection, cross-validation, and hyperparameter tuning techniques.

The California Housing Dataset from Scikit-Learn was used to build and evaluate regression models. The objective was to identify overfitting, improve model generalization, and select the best-performing model through systematic validation and optimization.

---

## Dataset

**California Housing Dataset**

The dataset contains information collected from California districts and is commonly used for regression tasks.

### Features

* MedInc (Median Income)
* HouseAge
* AveRooms
* AveBedrms
* Population
* AveOccup
* Latitude
* Longitude

### Target Variable

* Median House Value

---

## Project Workflow

### 1. Data Loading & Preprocessing

* Loaded the California Housing Dataset
* Performed feature-target separation
* Applied StandardScaler for feature scaling
* Split the dataset into training and testing sets

### 2. Baseline Model Training

The following regression models were trained and evaluated:

* Linear Regression
* Ridge Regression
* Decision Tree Regressor

### 3. Overfitting Detection

Training and testing performance were compared using RMSE.

A significant gap between training and testing error indicates overfitting, particularly in Decision Tree models.

### 4. Cross-Validation

5-Fold Cross Validation was applied using `cross_val_score()` to obtain a more reliable estimate of model performance across multiple data splits.

### 5. Hyperparameter Tuning

GridSearchCV was used to optimize the Decision Tree Regressor.

Hyperparameters tuned:

* `max_depth`
* `min_samples_split`

### 6. Model Evaluation

Models were evaluated using:

* RMSE (Root Mean Squared Error)
* R² Score

### 7. Model Comparison

Performance of all models was compared to identify the most suitable model for deployment.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-Learn
* Jupyter Notebook

---

## Key Machine Learning Concepts Covered

### Overfitting

Occurs when a model learns training data too closely and performs poorly on unseen data.

### Cross-Validation

A validation technique that evaluates model performance across multiple folds of the dataset to obtain a reliable estimate of generalization performance.

### Hyperparameter Tuning

The process of finding optimal model settings that improve predictive performance and reduce overfitting.

### GridSearchCV

An automated method that tests multiple hyperparameter combinations using cross-validation and selects the best-performing configuration.

---

## Learning Outcomes

Through this project, the following concepts were explored:

* Model Validation Techniques
* Overfitting and Underfitting Analysis
* Bias-Variance Tradeoff
* Cross-Validation
* Hyperparameter Optimization
* Regression Model Evaluation
* Model Selection and Comparison

---

## Conclusion

The project demonstrated how cross-validation and hyperparameter tuning can improve model reliability and generalization performance. By using GridSearchCV and systematic evaluation techniques, a more robust and optimized regression model was obtained for predicting California housing prices.
