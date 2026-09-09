Repository Overview:-

This repository is designed as a practical reference for learning and implementing fundamental Machine Learning algorithms.

Main Topics Covered:-

Data preprocessing and categorical data encoding

Label Encoding and Ordinal Encoding

Handling missing values

Reading CSV and Excel datasets

Train/Test splitting

Cross-validation

Leave-One-Out Cross-Validation (LOOCV)

Grid Search and hyperparameter tuning

Feature importance

K-Nearest Neighbors (KNN)

Decision Trees

Naive Bayes

Logistic Regression

Random Forest

Support Vector Machine (SVM)

Simple Linear Regression

Multiple Linear Regression

Random Forest Regression

K-Means clustering

K-Medoids clustering

Agglomerative/Hierarchical clustering

Dendrograms and linkage methods

Association rule mining

Apriori-based frequent itemset analysis

Datasets Included:-

The repository contains or references datasets used by the practical programs, including:

Iris dataset

Breast Cancer dataset

Wine dataset

Titanic dataset

Pima Indians Diabetes dataset

SpamBase dataset

Auto MPG dataset

Car/CO2 dataset

Glass dataset

Housing dataset

Colors/transaction dataset

Regression datasets

Machine Learning Workflow

Most practical programs follow a workflow similar to:

Dataset
   ↓
Data Loading
   ↓
Data Cleaning / Preprocessing
   ↓
Feature Selection
   ↓
Train-Test Split
   ↓
Model Training
   ↓
Prediction
   ↓
Model Evaluation
   ↓
Results / Visualization

Model Evaluation:-

Depending on the practical, different evaluation measures are used:

Classification:-

Accuracy

Confusion Matrix

Classification Report

Precision

Recall

F1-score

Cross-validation score

Regression:-

Mean Squared Error (MSE)

Root Mean Squared Error (RMSE)

R² Score

Clustering:-

Cluster assignments

Confusion matrix/classification report where labels are available

Cluster visualization

📂 Project Structure

Machine_Learning-main/
│
├── Practical Day 1/
│   ├── categorical1.py
│   ├── categorical2.py
│   ├── exp1.py
│   ├── exp2.py
│   ├── labelencoder1.py
│   ├── labelencoder_ordinal.py
│   └── readexcelandcsv.py
│
├── Practical Day 2/
│   ├── crossval.py
│   ├── featureimportance_decisiontree.py
│   ├── featureimportance_wine.py
│   ├── gridsearchCV.py
│   ├── gridwithcrossvalidation.py
│   └── loocv.py
│
├── Practical Day 3/
│   ├── knn_breastcancer.py
│   ├── knn_iris.py
│   └── testtrainsplit.py
│
├── Practical Day 4/
│   ├── decisiontree_breastcancer.py
│   ├── decisiontree_entropy.py
│   ├── decisiontree_iris.py
│   ├── naivebayes_breastcancer.py
│   └── naivebayes_iris.py
│
├── Practical Day 5/
│   ├── logistic_regression.py
│   ├── randomforest_breastcancer.py
│   └── svm_breastcancer.py
│
├── Practical Day 6/
│   ├── decision_tree.py
│   ├── knnAlgo.py
│   ├── logistic_regression.py
│   ├── naive_bayes.py
│   ├── random_forest.py
│   ├── SVM.py
│   └── Titanic Dataset/
│       ├── decision_tree.py
│       ├── knnAlgo.py
│       ├── logistic_regression.py
│       ├── naive_bayes.py
│       ├── random_forest.py
│       └── SVM.py
│
├── Practical Day 7/
│   ├── simpleregression_cpu.py
│   └── simpleregression_sal.py
│
├── Practical Day 8/
│   ├── multipleregression_carco2.py
│   ├── multipleregression_sample1.py
│   └── randomforest_autompgregression.py
│
├── Practical Day 9/
│   ├── GlassDataset/
│   ├── linearregression Dataset/
│   └── Multivariate_linear_regression_dataset/
│
├── Practical Day 10/
│   ├── K-Means programs
│   └── K-Medoids programs
│
├── Practical Day 11/
│   ├── agglomerative_titanic (1).py
│   ├── averagelinkage (1).py
│   ├── completelinkage (1).py
│   └── single linkage (1).py
│
└── Practical day 12/
    ├── association_color_rules1.py
    ├── association_color_rules2.py
    ├── association_rules_1 (1).py
    └── association_rules_2.py

