# Disease Prediction and Explainable AI (XAI) Project

Welcome to the Disease Prediction and Explainable AI (XAI) Project repository. This project focuses on early detection of diseases such as heart disease, breast cancer, and kidney disease using machine learning models, and emphasizes the importance of model interpretability through eXplainable Artificial Intelligence (XAI) frameworks.

## Introduction

The increasing mortality rates due to diseases like heart disease, breast cancer, and kidney disease highlight the necessity for early diagnosis. Leveraging Artificial Intelligence (AI) can automate this process; however, the black-box nature of many AI models raises concerns. To address this, we employed eXplainable Artificial Intelligence (XAI) frameworks—SHAP, LIME, and DALEX—to elucidate model predictions and enhance trust in AI-driven healthcare solutions.

## Datasets

We utilized five datasets encompassing:

- **Heart Disease**: Three distinct datasets. (UCI, Kaggle, Kaggle)
- **Breast Cancer**: One dataset. (WDBC)
- **Kidney Disease**: One dataset. (UCI)

Each dataset underwent preprocessing, including handling missing values, feature scaling, and splitting into training and testing sets.

## Machine Learning Models

Three machine learning algorithms were implemented:

- **Support Vector Machine (SVM)**
- **Logistic Regression (LR)**
- **K-Nearest Neighbors (KNN)**

The models were trained on each dataset, and the best-performing model for each was selected based on accuracy metrics.

## XAI Frameworks

To interpret and explain the predictions of our models, we applied three XAI frameworks:

- **SHAP (SHapley Additive exPlanations)**: Provides global and local interpretability by assigning each feature an importance value for a particular prediction. 

- **LIME (Local Interpretable Model-agnostic Explanations)**: Focuses on local interpretability by approximating the model locally with an interpretable model to explain individual predictions.

- **DALEX**: Offers tools to analyze and compare various models, focusing on global and local interpretability, and is particularly useful for comparing multiple predictive models.

