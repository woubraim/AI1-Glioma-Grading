# Project 1: Glioma Grading Using Clinical and Mutation Data
Overview

This project tackles glioma grading—a classification task to determine whether a brain tumor is Lower-Grade Glioma (LGG) or Glioblastoma Multiforme (GBM). The dataset includes both clinical data and mutation information for selected genes, helping to refine classification accuracy and potentially reduce testing costs by identifying the most predictive features.
Dataset

    Glioma Grading Dataset: Includes data on the top 20 mutated genes and 3 clinical features: Gender, Age_at_diagnosis, and Race.
    Each data point is labeled as either LGG or GBM.

Objectives

    1.Data Exploration and Preprocessing:
        Understand dataset structure, distributions, and handle any missing values.
        Encode categorical variables and apply scaling to numerical features.

    2.Data Splitting and Cross-validation:
        Split data into training (80%) and testing (20%) sets.
        Apply 10-fold cross-validation for robust model validation on the training data.

    3.Model Selection and Hyperparameter Tuning:
        Test and compare several classifiers: logistic regression, decision tree, random forest, and SVM.
        Use GridSearchCV to tune hyperparameters, optimizing model performance.

    4.Pipeline and Model Evaluation:
        Build pipelines to streamline preprocessing and model application.
        Evaluate model accuracy, specificity, sensitivity, and F1 score.
        Generate precision-recall and ROC curves to visualize model performance.

    5.Feature Importance Analysis:
        Determine which features are most impactful using feature importance analysis from decision tree and random forest models.

Requirements

    Packages: pandas, numpy, scikit-learn, matplotlib, seaborn
