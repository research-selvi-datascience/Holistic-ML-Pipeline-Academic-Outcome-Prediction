Academic Outcome Prediction Using Machine Learning

This project explores machine learning models for predicting student dropout and academic success using a real-world higher education dataset. The study aims to identify effective preprocessing and modeling strategies to improve prediction accuracy and understand underlying patterns in student data.

Key highlights:

Conducted eleven experiments applying varied preprocessing and modeling techniques

Explored dimensionality reduction methods: Principal Component Analysis (PCA) and Linear Discriminant Analysis (LDA)

Addressed class imbalance using resampling techniques including SMOTE, ADASYN, and NearMiss; SMOTE yielded the best results

Evaluated six traditional algorithms (Logistic Regression, SVM, Random Forest, Neural Networks, Decision Trees, K-Nearest Neighbors) under default and hyperparameter-tuned settings (via GridSearchCV) on both SMOTE and non-SMOTE datasets

Tested boosting algorithms (Gradient Boosting, XGBoost, CatBoost, LightGBM) with hyperparameter tuning using Optuna

Found tuned LightGBM and CatBoost models on SMOTE data outperformed traditional models in multiclass classification tasks

Performed outlier detection using Isolation Forest

Applied clustering (KMeans, KMedoids) after dimensionality reduction (PCA, t-SNE, Autoencoders), revealing patterns with moderate cluster separation (silhouette score ≈ 0.41)

Conducted binary classification (Graduate vs. Dropout), where traditional models on non-SMOTE data slightly outperformed boosting algorithms

For detailed code and experiments, please refer to the Jupyter notebooks in this repository.
