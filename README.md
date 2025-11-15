Effect of PCA on Model Accuracy and Training Time

A comparative study on how Principal Component Analysis (PCA) impacts the performance and computational cost of popular Machine Learning models.

🧠 Project Overview

This project analyzes the effect of dimensionality reduction using PCA on:

Model Accuracy

Training Time

Components vs Performance Trade-off

Three ML models were tested:

Logistic Regression

Support Vector Classifier (SVC)

Random Forest Classifier

The goal is to understand whether PCA improves performance, reduces overfitting, and speeds up training.

🏗️ Methodology
1️⃣ Preprocessing

Standard Scaling (StandardScaler)

PCA on multiple component counts

Train-test split

Iterative experiments for consistency

2️⃣ Models Evaluated

Logistic Regression

SVM (RBF)

Random Forest

3️⃣ Metrics Used

Accuracy

Training Time

Variance Explained

Component–Performance Curves

4️⃣ Visualizations

Accuracy vs Model

Training Time vs Components

Accuracy vs Training Time

PCA Variance Explained Curve

📈 Key Results
✔️ Logistic Regression

Best accuracy after PCA

PCA preserved linear separability

Training time significantly reduced

✔️ SVM

Slight drop in accuracy

PCA improved training speed

Non-linear models lose performance with PCA

✔️ Random Forest

Accuracy decreased

PCA didn’t improve trees

Training time benefited slightly

⭐ Overall Conclusion

PCA improves training speed for all models.
PCA preserves accuracy only for linear models.
Too many or too few components → accuracy drops.
Optimal region ≈ 95% variance retention.

📊 Professional Plots
Accuracy Comparison

Shows how different models behave after PCA.

Training Time vs Components

Demonstrates how PCA drastically reduces training cost.

Accuracy vs Training Time

Helps visualize the trade-off between performance and speed.

PCA Explained Variance Curve

Shows the ideal number of components needed to retain information.

(Plots are generated via the code in the notebook.)

📁 Tech Stack

Python

Scikit-learn (PCA, ML models)

Matplotlib & Seaborn

NumPy / Pandas

🧪 How to Run
pip install numpy pandas scikit-learn matplotlib seaborn


Run the notebook:

jupyter notebook pca_analysis.ipynb

📌 Future Work

Compare PCA with t-SNE / UMAP

Try PCA before Deep Learning

Hyperparameter tuning with PCA

Analyze bias–variance changes

👤 Author

Aman Pal
B.S. Student, IIT Patna
Focus: Machine Learning, NLP Research
