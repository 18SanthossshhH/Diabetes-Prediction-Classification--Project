# Diabetes-Prediction-Classification-Project

This is a classification project, and the goal is to diagnose whether or not a patient has diabetes.This project is based on real-world data and dataset is also highly imbalanced. Learn more about detailed description and problem with tasks performed.

**Description:** This dataset comes from the National Institute of Diabetes and Digestive and Kidney Diseases and contains under-representative data samples. All the sensitive information has been excluded during data encoding and finally it has 9 features and 768 data of the patient.It is then preprocessed and subjected to analysis using various machine learning classification techniques in order to determine the principal causes of diabetes.

**Source of dataset:** [Link to the dataset](https://www.kaggle.com/datasets/akshaydattatraykhare/diabetes-dataset)

**Problem Statement:** The target feature is Outcome variable. The aim is to sequentially classify this variable using the other 8 attributes. The Roc Auc score will be the evaluation metric.

### Tasks and techniques used:

**1. Exploratory data analysis**
- Data analysis using `Pandas`
- Exploratory data analysis using `matplotlib` and `seaborn`

**2. Data preparation and pre-processing**
- Missing Values Tretment using fillna method
- One Hot encoding using pandas get_dummies
- Feature selection using `chi2` statistic and SelectKBest method
- PCA to reduce dimentinality
- Imbalance data tretment using `SMOTENC` technique

**3. Modelling using sci-kit learn library**
- Baseline model using `RandomForest` & `LogisticRegression` using default technique 
- Tuned hyperparameters using `n_estimators`,`min_samples_leaf` and `max_depth` parameters for Randomforest model 

**4. Evaluation**
- Evaluation metric was `roc_auc_score` 
- Baseline model evaluation `roc_auc_score = 78%`
- Final model evaluation `roc_auc_score = 87%`

### Acknowledgement: [TMLC Academy](https://www.themlco.com/Academy/index.html)

### References:

1. [Machine learning mastery](https://machinelearningmastery.com/feature-selection-with-categorical-data/)
2. [Feature engieering techniques](https://towardsdatascience.com/feature-engineering-for-machine-learning-3a5e293a5114)
