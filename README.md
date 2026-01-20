# Stroke History Classification from BRFSS Risk Factors (R)

# Overview
This project builds and evaluates supervised machine learning models to classify stroke history using risk-factor variables from the 2015 Behavioral Risk Factor Surveillance System (BRFSS).

# Data
- Source: BRFSS (2015) public-use data
- Note: Raw data are not included in this repository. Please download from the CDC BRFSS website and place files in the location described below.

# Methods
- Data cleaning and preprocessing
- Train/test split (stratified)
- 3-fold cross-validation for model tuning
- Models evaluated: logistic regression, random forest, SVM, Naive Bayes, boosting
- Metrics: AUC, accuracy, sensitivity, specificity

# Key Results 
- Ensemble/tree-based methods performed best overall.
- Results were compared across multiple classification metrics to balance performance and interpretability.
 
