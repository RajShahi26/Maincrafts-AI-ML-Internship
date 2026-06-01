# 🏠 House Price Prediction – Model Comparison

## 📌 Project Overview

This project was completed as part of the **Artificial Intelligence & Machine Learning Internship – Task 2**.

The objective was to build and compare multiple machine learning regression models for predicting house prices using the California Housing Dataset. The project focuses on feature engineering, feature scaling, model optimization, and performance evaluation.

---

## 🎯 Objectives

* Load and preprocess the California Housing Dataset
* Apply feature scaling using StandardScaler
* Train multiple regression models
* Evaluate model performance using RMSE and R² Score
* Compare model performance
* Visualize prediction results
* Identify the best-performing model

---

## 📊 Dataset

The project uses the **California Housing Dataset** available through Scikit-Learn.

### Features

* Median Income
* House Age
* Average Rooms
* Average Bedrooms
* Population
* Average Occupancy
* Latitude
* Longitude

### Target Variable

* Median House Value

---

## ⚙️ Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Scikit-Learn
* Jupyter Notebook

---

## 🔄 Project Workflow

### 1. Data Loading

The California Housing Dataset was loaded using Scikit-Learn.

### 2. Data Preprocessing

* Feature and target separation
* Train-test split
* Feature scaling using StandardScaler

### 3. Model Training

The following regression models were implemented:

* Linear Regression
* Ridge Regression
* Decision Tree Regressor

### 4. Model Evaluation

Performance was measured using:

* RMSE (Root Mean Squared Error)
* R² Score

---

## 📈 Model Performance Comparison

| Model                   | RMSE     | R² Score |
| ----------------------- | -------- | -------- |
| Linear Regression       | 0.745581 | 0.575788 |
| Ridge Regression        | 0.745554 | 0.575819 |
| Decision Tree Regressor | 0.724234 | 0.599732 |

---

## 🏆 Best Performing Model

### Decision Tree Regressor

Performance:

* RMSE = **0.724234**
* R² Score = **0.599732**

The Decision Tree Regressor achieved the lowest prediction error and the highest explanatory power among the evaluated models.

---

## 📊 Visualizations

The project includes:

* RMSE Comparison Bar Chart
* R² Score Comparison Bar Chart
* Actual vs Predicted Values Scatter Plot
* Model Performance Comparison

---

## 🚀 How to Run

### Clone the Repository

```bash
git clone <repository-url>
cd <repository-folder>
```

### Create Virtual Environment

```bash
python -m venv ml_env
```

### Activate Virtual Environment

#### Windows

```bash
ml_env\Scripts\activate
```

#### Linux/macOS

```bash
source ml_env/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

```text
AI_ML_Task2_Model_Comparison.ipynb
```

---

## 📂 Repository Structure

```text
├── AI_ML_Task2_Model_Comparison.ipynb
├── README.md
├── requirements.txt
├── images/
│   ├── rmse_comparison.png
│   ├── r2_comparison.png
│   └── actual_vs_predicted.png
└── report.pdf
```

---

## 📚 Learning Outcomes

Through this project, I gained practical experience in:

* Data preprocessing
* Feature scaling
* Regression modeling
* Model comparison
* Performance evaluation
* Data visualization
* Machine Learning workflow implementation

---

## 👨‍💻 Author

**Raj Shahi**

Artificial Intelligence & Machine Learning Internship Project

---

## 📜 License

This project is created for educational and internship purposes.
