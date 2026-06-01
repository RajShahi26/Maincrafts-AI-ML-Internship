# Artificial Intelligence & Machine Learning – Task 2 Report

## Title

Feature Engineering, Model Optimization and Performance Comparison for House Price Prediction using the California Housing Dataset

## Objective

The objective of this project was to develop and compare multiple machine learning regression models for predicting house prices using the California Housing Dataset. The task focused on data preprocessing, feature scaling, model training, performance evaluation, and model comparison.

---

## Dataset Description

The California Housing Dataset was used for this project. The dataset contains various housing-related features such as:

* Median Income
* House Age
* Average Rooms
* Average Bedrooms
* Population
* Average Occupancy
* Latitude
* Longitude

The target variable is the median house value of California districts.

---

## Methodology

### 1. Data Loading

The California Housing Dataset was loaded using the Scikit-Learn library.

### 2. Data Preprocessing

The dataset was divided into feature variables (X) and target variable (y). To ensure that all features contributed equally during model training, feature scaling was performed using the StandardScaler technique.

### 3. Train-Test Split

The dataset was split into training and testing sets using an 80:20 ratio. The training dataset was used to train the machine learning models, while the testing dataset was used to evaluate model performance.

### 4. Model Development

Three regression models were implemented and trained:

1. Linear Regression
2. Ridge Regression
3. Decision Tree Regressor

### 5. Model Evaluation

The models were evaluated using the following performance metrics:

* Root Mean Squared Error (RMSE)
* Coefficient of Determination (R² Score)

RMSE measures prediction error, while R² Score indicates how well the model explains the variance in the target variable.

---

## Results

| Model                   | RMSE     | R² Score |
| ----------------------- | -------- | -------- |
| Linear Regression       | 0.745581 | 0.575788 |
| Ridge Regression        | 0.745554 | 0.575819 |
| Decision Tree Regressor | 0.724234 | 0.599732 |

---

## Performance Analysis

The results indicate that the Decision Tree Regressor achieved the best overall performance among the three evaluated models.

Linear Regression and Ridge Regression produced very similar results, indicating that regularization had only a minor impact on performance for this dataset. The Decision Tree Regressor was able to capture non-linear relationships within the housing data, resulting in improved predictive accuracy.

The Decision Tree model achieved the lowest RMSE value of 0.724234 and the highest R² score of 0.599732, making it the most effective model for this prediction task.

---

## Visualization

Several visualizations were generated to analyze model performance:

* RMSE Comparison Bar Chart
* R² Score Comparison Bar Chart
* Actual vs Predicted Values Scatter Plot
* Feature Importance Plot (Decision Tree Regressor)

The Actual vs Predicted plot demonstrated that the Decision Tree Regressor produced predictions that closely followed the actual housing prices.

---

## Conclusion

This project successfully implemented feature engineering, feature scaling, and machine learning model comparison techniques using the California Housing Dataset.

Three regression models were trained and evaluated using RMSE and R² Score metrics. Among all the models, the Decision Tree Regressor demonstrated the best performance with:

* RMSE = 0.724234
* R² Score = 0.599732

These results indicate that the Decision Tree Regressor was better able to capture the underlying patterns and non-linear relationships present in the housing dataset compared to Linear Regression and Ridge Regression.

Therefore, the Decision Tree Regressor is recommended as the most suitable model for house price prediction in this study.

---

## Tools and Libraries Used

* Python
* NumPy
* Pandas
* Matplotlib
* Scikit-Learn
* Jupyter Notebook

---

## References

1. Scikit-Learn Official Documentation
2. California Housing Dataset Documentation
3. NumPy Documentation
4. Pandas Documentation
5. Matplotlib Documentation
6. Python Official Documentation

