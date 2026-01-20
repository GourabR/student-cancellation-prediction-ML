# Student Cancellation Prediction (ML)

## Overview
Built an end-to-end Machine Learning model to predict students likely to cancel their admission using academic engagement, attendance, test behavior, and payment signals.

This project was developed at **Physics Wallah Ltd.** to proactively identify at-risk students.

## Key Highlights
- Achieved **~60% Precision@K** for top-risk students
- Overall model accuracy of **~95%**
- Optimized for **business actionability**, not generic accuracy
- First ML initiative of its kind within the organization

## Modeling Approach
- Started with Logistic Regression (baseline)
- Shifted to **Histogram Gradient Boosting** to capture non-linear patterns
- Optimized **Precision@K** instead of recall/accuracy due to class imbalance

## Key Features Used
- Attendance %
- Test participation & unattempted tests
- Payment stage behavior
- Early disengagement flags
- Marks vs attendance risk signals

## Evaluation Metrics
- Precision@K
- Accuracy
- Confusion Matrix (TN / FP / FN / TP)

> ⚠️ SQL queries and internal data sources are excluded for confidentiality.

## Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- Jupyter Notebook
