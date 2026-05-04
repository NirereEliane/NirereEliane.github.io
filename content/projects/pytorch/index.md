---
title: Material-classification-for-Clean-energy
date: 2023-10-26
links:
  - type: site
    url: https://github.com/NirereEliane/Material-classification-for-Clean-energy
tags:
  # - Hugo
  # - HugoBlox
  - Supervised Learning
  - K‑Means Clustering
  - XGBoost
  - Scikit‑learn
  - Markdown
---

This project focuses on material classification for clean energy applications using data‑driven machine learning techniques. As clean energy technologies advance, new materials must be synthesized and accurately characterized to improve system efficiency, reliability, and performance. The objective of this work is to predict material classes based on their molecular properties, using both classical and advanced machine learning models.
Two datasets are provided: one containing the molecular properties of materials and another listing their corresponding material classes. The project adopts a data scientist’s workflow that includes data preprocessing, visualization, model development, evaluation, and optimization to achieve the highest possible classification accuracy.
The study begins with data visualization and unsupervised learning, where techniques such as Principal Component Analysis (PCA) and K‑means clustering are used to explore the structure of the data and assess whether material classes can be separated based on molecular features. These methods help reduce dimensionality, identify latent patterns, and provide insight into class overlap.
Next, multiple supervised classification algorithms are implemented, including Decision Trees, Random Forests, and K‑Nearest Neighbors (KNN). Model performance is evaluated using accuracy, F1‑score, and confusion matrices, enabling a clear comparison of their predictive capabilities. In addition, features derived from PCA and K‑means clustering are incorporated into the classifiers to evaluate whether they improve classification performance.
To further enhance predictive accuracy, hyperparameter tuning is carried out for Random Forest and KNN models using a fixed random seed to ensure reproducibility. The best‑performing configurations and their corresponding hyperparameters are reported.
Feature importance analysis is then conducted to determine which molecular properties contribute most significantly to classification accuracy. The Random Forest model is retrained using different subsets of top‑ranked features to study how model performance changes as the number of features varies.
Advanced models are also explored. XGBoost, an optimized gradient‑boosting framework, is implemented and tuned to assess its performance relative to traditional classifiers. Additionally, a neural network classifier is developed using deep learning frameworks such as TensorFlow or PyTorch. The network architecture is systematically adjusted by varying the number of layers and neurons to examine how model complexity affects classification accuracy.
Overall, this project demonstrates how machine learning can be used to classify materials for clean energy applications, compares traditional and modern modeling techniques, and highlights the importance of feature selection, model tuning, and evaluation. The results provide insight into which algorithms and features are most effective for predicting material classes based on molecular properties.

<!--more-->
