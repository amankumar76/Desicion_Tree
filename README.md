# Decision Tree Learning Project

## Overview
This repository demonstrates my understanding of **Decision Tree algorithms** for both **classification** and **regression** tasks. The project includes dataset exploration, model training, evaluation, hyperparameter tuning, and real-world applications.

---

## Key Concepts
- **Decision Trees**: How they work for classification and regression tasks.
- **Impurity Measures**: Concepts of **Gini Impurity** and **Entropy** for selecting splits.
- **Pruning Techniques**: Pre-Pruning vs Post-Pruning to reduce overfitting.
- **Information Gain**: Metric for choosing the best split.
- **Hyperparameter Tuning**: Optimizing model performance using `max_depth`, `min_samples_split`, and `GridSearchCV`.

---

## Datasets
1. **Iris Dataset** – Classification task.  
   Source: `sklearn.datasets.load_iris()` or CSV file.  
2. **Boston Housing Dataset** – Regression task.  
   Source: `sklearn.datasets.load_boston()` or CSV file.  
3. **California Housing Dataset** – Regression task with real-world data.  
   Source: `sklearn.datasets.fetch_california_housing()`  

---

## Python Implementation
The project includes Python programs to:
- Load and explore datasets.
- Train Decision Tree models for classification and regression.
- Evaluate models using **accuracy**, **Mean Squared Error (MSE)**, and **feature importance**.
- Compare fully-grown trees vs pruned trees.
- Tune hyperparameters with **GridSearchCV**.

Libraries used: `scikit-learn`, `pandas`, `numpy`, `matplotlib` / `seaborn`.

---

## Real-World Applications
- Predicting healthcare outcomes (disease prediction)
- Financial risk assessment
- Customer churn prediction
- Sales and marketing forecasting

Decision Trees are highly interpretable and can handle both **categorical** and **numerical data**, making them practical for many business scenarios.

---

## Project Structure
