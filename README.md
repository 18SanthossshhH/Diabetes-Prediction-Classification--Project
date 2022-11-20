# Diabetes-Prediction-Classification-Project

This is a classification project, and the goal is to diagnose whether or not a patient has diabetes.This project is based on real-world data and dataset is also highly imbalanced. Learn more about detailed description and problem with tasks performed.

**Description:** This dataset comes from the National Institute of Diabetes and Digestive and Kidney Diseases and contains under-representative data samples. All the sensitive information has been excluded during data encoding and finally it has 9 features and 768 data of the patient.It is then preprocessed and subjected to analysis using various machine learning classification techniques in order to determine the principal causes of diabetes.

**Source of dataset:** [Link to the dataset](https://www.kaggle.com/datasets/akshaydattatraykhare/diabetes-dataset)

**Problem Statement:** The target feature is `Outcome` variable. The aim is to sequentially classify this variable using the other 8 attributes. The Roc Auc score will be the evaluation metric.

### Tasks and techniques used:

**1. Exploratory data analysis**
- Data analysis using `Pandas`
- Exploratory data analysis using `matplotlib` and `seaborn`

**2. Data preparation and pre-processing**
- Zero / Inappropriate Values Tretment with Median values

**3. Modelling using sci-kit learn library**
- Baseline model using `RandomForest` & `LogisticRegression` using default technique 
- Tuned hyperparameters using `n_estimators`,`min_samples_leaf` and `max_depth` parameters for Randomforest model 

**4. Evaluation**
- Evaluation metric was `roc_auc_score` 
- Baseline model evaluation `roc_auc_score = 78%`
- Final model evaluation `roc_auc_score = 87%`

### References:

1. [The Model Performance Mismatch Problem]([https://machinelearningmastery.com/feature-selection-with-categorical-data/](https://machinelearningmastery.com/the-model-performance-mismatch-problem/))
2. [Sllearn Model selection-Cross_val_score]([https://towardsdatascience.com/feature-engineering-for-machine-learning-3a5e293a5114](https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.cross_val_score.html))
