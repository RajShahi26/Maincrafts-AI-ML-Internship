# Linear Regression Model using California Housing Dataset

## Project Overview

This project demonstrates the implementation of a **Linear Regression** model using the **California Housing Dataset** from Scikit-learn. The goal is to predict median house prices based on different housing-related features.

---

## Dataset Used

The dataset used in this project is:

* **California Housing Dataset**
* Source: `sklearn.datasets.fetch_california_housing`

---

## Technologies and Libraries Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

## Project Workflow

### 1. Data Loading

The California Housing dataset was loaded using Scikit-learn.

### 2. Data Preprocessing

* Converted dataset into Pandas DataFrame
* Checked missing values
* Explored dataset structure

### 3. Exploratory Data Analysis (EDA)

Performed:

* Statistical analysis using `describe()`
* Correlation heatmap
* Histogram plots
* Boxplots for outlier detection
* Scatter plots

### 4. Feature Selection

Features (`X`) and target variable (`y`) were separated.

### 5. Train-Test Split

Dataset was divided into:

* Training Data
* Testing Data

using `train_test_split()`.

### 6. Model Training

Implemented Linear Regression using:

```python
from sklearn.linear_model import LinearRegression
```

### 7. Model Evaluation

Model performance was evaluated using:

* R² Score
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)

### 8. Visualization

Compared Actual vs Predicted values using scatter plots.

---

## Key Learning Outcomes

* Understanding Linear Regression
* Data preprocessing
* EDA techniques
* Outlier detection
* Correlation analysis
* Model evaluation metrics
* Git and GitHub workflow

---

## Repository Structure

```text
├── task1_ml_linear_regression.ipynb
├── README.md
├── .gitignore
```

---

## Author

Raj Shahi

---

## Conclusion

The Linear Regression model was successfully implemented on the California Housing Dataset. The project helped in understanding the complete Machine Learning workflow from data preprocessing to model evaluation and visualization.
