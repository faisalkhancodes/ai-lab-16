# AI Lab 16: Linear Regression Machine Learning System

[cite_start]This repository contains the complete implementation of **Lab 14: Linear Regression using Python and Scikit-Learn** for the Artificial Intelligence Lab course[cite: 1, 2].

---

## 👨‍🎓 Student Profile
* **Name:** Faisal Khan
* **Enrollment ID:** 01-131232-105
* **Faculty Instructor:** Engr. Saad Mazhar Khan

---

## 🚀 Lab Objectives
[cite_start]This lab covers the comprehensive lifecycle of implementing, optimizing, and evaluating a classic linear regression model[cite: 4]:
* [cite_start]**Mathematical Foundations:** Visualizing regression lines and residual error spreads[cite: 6].
* [cite_start]**Optimization from Scratch:** Implementing the Gradient Descent algorithm manually to study hyperparameter convergence behaviors[cite: 7, 8].
* [cite_start]**Framework Deployment:** Training, predicting, and extracting weights using the Scikit-Learn library[cite: 9].
* [cite_start]**Statistical Evaluation:** Analyzing model accuracy using key evaluation metrics like MAE, MSE, RMSE, and $R^2$ Score[cite: 10].

---

## 🛠️ Tasks Completed

### 🔹 Task 1 & 2: Structural Concepts & Cost Functions
* [cite_start]**Core Definition:** Formulated a clean definition of how a continuous target variable maps to independent features via an optimized line of best fit[cite: 14, 15, 16].
* [cite_start]**Residual Analysis:** Calculated and plotted the residual vertical error matrix ($y - \hat{y}$)[cite: 18, 19, 20].
* [cite_start]**Mathematical Cost:** Modeled the Mean Squared Error (MSE) formula to penalize large outlier residuals[cite: 21, 22]:
  $$MSE = \frac{1}{n} \sum_{i=1}^{n} (y_i - \hat{y}_i)^2$$

### 🔹 Task 3 & 4: Manual Gradient Descent Optimization
* [cite_start]**Coded from Scratch:** Coded the weight update loop and bias adjustments manually using NumPy matrix math[cite: 23, 24].
* [cite_start]**Learning Rate Exploration:** Documented convergence behaviors across multiple learning rates ($0.01$, $0.1$, and $0.5$)[cite: 25, 26].
* [cite_start]**Key Finding:** Proved that an aggressive learning rate ($0.5$) overshoots the global minimum causing severe divergence, while $0.1$ delivers rapid, smooth convergence[cite: 27, 30].

### 🔹 Task 5 & 6: Scikit-Learn Pipeline & Performance Metrics
* [cite_start]**Model Training:** Deployed Scikit-Learn's `LinearRegression` engine to output mathematically sound coefficients and intercept values[cite: 32, 33, 34].
* [cite_start]**Insight Evaluation:** Verified a definitive positive linear relationship between *Years of Experience* and *Salary* scales[cite: 35, 36].
* [cite_start]**Error Analysis:** Generated concrete metric values to prove real-world predictive reliability[cite: 37, 38]:
  * [cite_start]**Mean Absolute Error (MAE):** Measures average absolute error magnitudes[cite: 10].
  * [cite_start]**Root Mean Squared Error (RMSE):** Flags model performance in actual currency units[cite: 10].
  * [cite_start]**$R^2$ Score (Coefficient of Determination):** Measures total accounted data variance scaled safely between $0$ and $1$[cite: 10].

### 🔹 Task 7 & 8: LINE Assumptions & Critical Thinking
* [cite_start]**Assumptions Check:** Documented the core **LINE** rules (Linearity, Independence, Normality, and Equal Variance)[cite: 41, 42].
* [cite_start]**Diagnostic Check:** Created residual error distribution charts to confirm normal data tendencies[cite: 43, 44].
* [cite_start]**Engineering Review:** Summarized core concepts of model overfitting/underfitting, data scaling requirements for swift gradient steps, and train-test partitioning tactics to validate against unseen target matrices[cite: 46, 47, 49].

---

## 💻 Environment & Tech Stack
* **Language:** Python 3.14
* [cite_start]**Core Toolkits:** `NumPy`, `Pandas`, `Matplotlib`, `Scikit-Learn` [cite: 2]
* [cite_start]**Development Platform:** VS Code Jupyter Notebook Environment (`.ipynb`) [cite: 2, 51]
