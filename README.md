# L1-L2-Regularization
# 📉 Handling Overfitting: L1 & L2 Regularization

This repository demonstrates the implementation of **Lasso (L1)** and **Ridge (L2)** Regularization techniques. The project explores how to prevent a model from "memorizing" noise in the training data (overfitting) by penalizing large coefficients, resulting in more robust and reliable predictions.

---

## 🛠️ The Regularization Stack
* **Python**: Core logic.
* **Pandas & NumPy**: For data cleaning and feature engineering.
* **Scikit-Learn**: For `LinearRegression`, `Lasso` (L1), and `Ridge` (L2) models.
* **Matplotlib & Seaborn**: For visualizing data distribution and model performance.

---

## 🧠 Key Concepts Implemented

### 1. The Overfitting Problem
* Initialized a standard **Linear Regression** model which showed high accuracy on training data but significantly lower accuracy on test data (a classic sign of overfitting).

### 2. L1 Regularization (Lasso Regression)
* **Mechanism:** Adds a penalty equal to the *absolute value* of the magnitude of coefficients.
* **Feature Selection:** Demonstrated how Lasso can shrink some coefficients exactly to zero, effectively acting as an automated feature selection tool.
* **Equation:** $Cost = MSE + \lambda \sum |w_i|$

### 3. L2 Regularization (Ridge Regression)
* **Mechanism:** Adds a penalty equal to the *square* of the magnitude of coefficients.
* **Coefficient Shrinkage:** Demonstrated how Ridge keeps all features but minimizes their impact, which is ideal when you have many small but important features.
* **Equation:** $Cost = MSE + \lambda \sum w_i^2$

---

## 📊 Project Workflow
* **Data Cleaning:** Handled missing values and performed One-Hot Encoding on the Melbourne Housing dataset.
* **Baseline Model:** Trained a basic Linear Regression model to identify overfitting.
* **Optimization:** Applied Lasso and Ridge models with tuned `alpha` (lambda) values to improve test scores and bridge the gap between training and testing performance.

---

## 📈 Why use Regularization?
* **Generalization:** Ensures the model performs well on unseen real-world data.
* **Multicollinearity:** Helps manage datasets where features are highly correlated.
* **Complexity Control:** Allows the user to control the "simplicity" of the model using the `alpha` hyperparameter.

---

## 🚀 How to Run

1. **Clone the repo:**
   ```bash
   git clone [https://github.com/Manaswi9123/Python-DataScience-Fundamentals.git](https://github.com/Manaswi9123/Python-DataScience-Fundamentals.git)
