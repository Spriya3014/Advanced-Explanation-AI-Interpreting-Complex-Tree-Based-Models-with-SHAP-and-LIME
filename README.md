# Advanced-Explanation-AI-Interpreting-Complex-Tree-Based-Models-with-SHAP-and-LIME
## Project Overview

This project focuses on interpreting complex tree-based machine learning models using advanced Explainable AI methods — SHAP and LIME.
Tree-based ensembles (XGBoost, Random Forests, LightGBM) deliver high performance but behave like black boxes. This project makes them understandable by generating both global and local explanations.

SHAP provides global feature importance and visual explanations, while LIME delivers local, human-friendly instance-level interpretations.

## Key Features
SHAP Global Interpretability

Summary plot

Bar plot

Feature impact analysis

Local Interpretability with SHAP & LIME

Force plots

LIME local explanations

Instance-level comparison

Model Evaluation

AUC, Precision, Recall, F1-score

Threshold optimization

Output Saving

All SHAP & LIME results saved automatically

Organized output folder

## Model Performance
Validation Metrics

AUC: 0.740

F1-score: 0.471

Precision: 0.477

Recall: 0.466

Test Metrics

AUC: 0.786

F1-score: 0.506

Precision: 0.633

Recall: 0.422

Best Threshold

Threshold: 0.43

Improved Validation F1: 0.587

## Explainability Workflow
1. SHAP Global Explanations

Identify top features

Understand global model behavior

Generate summary and bar plots

2. SHAP & LIME Local Explanations

High-confidence positive

High-confidence negative

Low-confidence prediction

Compare feature contributions

3. SHAP vs LIME Comparison

Agreement and differences

Stability vs interpretability

Impact of non-linear feature interactions

## Technologies Used

Python

NumPy, Pandas

SHAP

LIME

Scikit-learn

XGBoost / LightGBM

Matplotlib, Seaborn

Pickle

SHAP force plots for 3 selected instances

LIME explanations

Model performance reports
