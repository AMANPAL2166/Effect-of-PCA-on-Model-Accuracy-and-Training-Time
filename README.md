# Effect of PCA on Model Accuracy and Training Time

## A practical experiment analyzing how Principal Component Analysis (PCA) impacts
## accuracy, training speed, and dimensionality across different ML models.

# Overview

This project evaluates the effect of PCA on three supervised models:

Logistic Regression

Support Vector Classifier (SVC)

Random Forest Classifier

We compare performance across multiple PCA component sizes
to identify the best trade-off between speed and accuracy.

Standardize features using StandardScaler

Apply PCA (5, 10, 15, 20, 25, 30 components)

Train 3 ML models on each PCA output

Measure

Accuracy

Training time

Generate plots for comparison

# Tech Stack

Python, NumPy, Pandas, Scikit-learn, Matplotlib, Seaborn

# 📝 Key Insights

PCA significantly reduces training time

PCA preserves accuracy for linear models

Random Forest does not improve with PCA

Optimal results around 90–95% explained variance
