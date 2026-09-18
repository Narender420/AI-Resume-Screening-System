# AI Resume Screening System — Week 4: ML Model Selection & Evaluation Plan

Virtual Data Science Apprentice — Python Specialist Intern (Week 4 of 4)

## Overview

This week's deliverable defines the machine learning model selection and evaluation plan for the **AI Resume Screening System**, covering both the resume-category classification task and the resume-to-job-description matching task.

## Objective

Create a strategic plan for selecting and evaluating ML models in Python — covering model choice criteria, evaluation metrics, and the training/validation process — to guide the execution phase of the project.

## What's in This Report

- **Candidate approaches** — Logistic Regression, Multinomial Naive Bayes, linear-kernel SVM, Random Forest/Gradient Boosting, and cosine similarity over embeddings for the matching sub-task, with strengths and ideal use case for each.
- **Model selection criteria** — predictive performance, interpretability, training/inference time, robustness to a small dataset.
- **Evaluation metrics** — macro-averaged F1 (primary), precision, recall, accuracy, and confusion matrix for classification; cosine similarity and Precision@K for matching.
- **Training, tuning, and validation process** — stratified 80/20 split → baseline training → 5-fold cross-validation → hyperparameter tuning (Grid/RandomizedSearchCV) → final model selection → single held-out test evaluation.
- **Overfitting risk and mitigation** — leakage-safe vectorization, cross-validation-only tuning, single final test-set touch.
- **Practical applicability and limitations** — positions the system as a hiring decision-support aid requiring bias audits and human review before real-world use.

## Deliverable

| File | Description |
|---|---|
| `Week4_ML_Model_Selection_and_Evaluation_Plan.docx` | Full model selection & evaluation plan (Word document) |

## Tech Stack

Python · scikit-learn (Logistic Regression, Naive Bayes, SVM, Random Forest, GridSearchCV) · XGBoost (optional) · sentence-transformers (optional)

## Status

✅ Week 4 complete — internship deliverables finalized across all 4 weeks.

## Author

[Your Full Name]
