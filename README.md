# my_project-changes
# Diabetes Prediction Using Machine Learning

## Table of Contents
1. [Abstract](#abstract)
2. [Introduction](#introduction)
3. [Machine Learning Models](#machine-learning-models)
4. [Conclusion](#conclusion)
5. [Future Work](#future-work)

---

## Abstract
Diabetes is a chronic disease affecting millions worldwide. This project explores the use of machine learning to predict diabetes based on medical and demographic features. Three models—XGBoost, Random Forest, and Logistic Regression—were trained and evaluated using accuracy, precision, recall, and F1-score. Data balancing techniques like SMOTE were applied to improve performance. Results indicate that XGBoost performed best, achieving a **97.57% accuracy**.

---

## Introduction
Early diabetes prediction can enhance patient outcomes and reduce healthcare costs. Traditional methods, like blood tests, are resource-intensive. Machine learning offers a faster, data-driven alternative. This study compares **XGBoost, Random Forest, and Logistic Regression** on a structured dataset, assessing their effectiveness in diabetes classification.

---


## Machine Learning Models
This project uses three popular classification models:

### 1. **XGBoost (Extreme Gradient Boosting)**
   - A powerful **ensemble learning algorithm** that uses gradient boosting.
   - Handles missing values and complex feature interactions well.
   - Achieved the **highest accuracy (97.57%)**, making it the best performer.

### 2. **Random Forest**
   - A **bagging-based ensemble method** that builds multiple decision trees.
   - Reduces overfitting by averaging predictions from multiple trees.
   - Performed slightly worse than XGBoost, with an **accuracy of 96.95%**.

### 3. **Logistic Regression**
   - A **linear model** used for binary classification.
   - Simple and interpretable but struggled with the dataset’s complexity.
   - Achieved an **accuracy of 89.26%**, making it the weakest performer.

---

## Conclusion
XGBoost and Random Forest significantly outperformed Logistic Regression, with **97.57% and 96.95% accuracy, respectively**. Their precision, recall, and F1-score were consistently high. Logistic Regression, at **89.26% accuracy**, struggled to handle data complexity. Overall, **XGBoost proved the most reliable** model for diabetes prediction.

---

## Future Work
Further improvements can be made by:
- **Hyperparameter tuning** for XGBoost and Random Forest using grid/random search.
- **Ensemble techniques** like boosting or stacking for enhanced performance.
- **Feature engineering** to create new predictive variables.
- Exploring advanced models like **LightGBM and CatBoost** for structured data classification.

---

 
📌 **Dataset Source:** [Kaggle - Diabetes Prediction Dataset](https://www.kaggle.com/datasets/iammustafatz/diabetes-prediction-dataset)  
🔗 **GitHub Repository:** [https://github.com/gollamanasa23/my_project-changes.git]
