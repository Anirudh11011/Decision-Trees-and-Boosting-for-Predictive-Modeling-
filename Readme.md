# Project Title: Decision Trees and Boosting for Predictive Modeling

## Project Overview
This project focuses on implementing core machine learning algorithms from scratch—**Decision Trees**, **Random Forests**, and **AdaBoost**—to perform binary classification on the Titanic dataset.  
The goal was to deepen understanding of tree-based models and ensemble techniques while developing a full ML workflow, including preprocessing, training, evaluation, and performance comparison.

---

## Key Features and Implementations

### 1. Custom Decision Tree Classifier
- Implemented from scratch using **NumPy** with support for **Gini**, **Entropy**, and **Misclassification** splitting criteria.
- Designed **recursive tree-building** and **sample prediction** methods.

### 2. Random Forest Ensemble
- Built an ensemble of custom decision trees with **bootstrapped sampling** and **feature subsetting**.
- Aggregated predictions using **majority voting** to improve generalization.

### 3. AdaBoost Algorithm
- Implemented the boosting logic manually, **reweighting training instances** across iterations.
- Combined weak learners into a strong classifier using **weighted majority voting**.

### 4. Titanic Dataset Analysis
- Loaded and preprocessed the dataset, handling missing values, encoding categorical features, and dropping irrelevant columns.
- Performed **one-hot encoding** and filled missing data using **median/mode** strategies.

### 5. Data Splitting and Evaluation
- Split data into training and testing sets using `scikit-learn`’s **train_test_split**.
- Evaluated models using **accuracy** as the main metric.

### 6. Model Comparison and Analysis
- Compared individual model performance and analyzed trade-offs between **model complexity** and **accuracy**.
- Reported **test accuracies** for Decision Tree and Random Forest classifiers.

### 7. Manual Workflow Using Core Python Libraries
- Used **NumPy**, **Pandas**, and basic Python structures to implement ML pipelines without relying on high-level ML frameworks.
- Reinforced low-level understanding of **model training and inference**.

### 8. End-to-End Predictive Modeling
- Built the entire classification system from **data loading** to **final evaluation**.
- Gained hands-on experience in developing **interpretable** and **efficient** predictive models.

---

## Conclusion
This project showcases a deep understanding of core machine learning concepts through **end-to-end implementation** of decision trees and ensemble methods.  
It demonstrates **algorithmic thinking**, **attention to detail**, and the ability to **build ML systems from scratch**.
