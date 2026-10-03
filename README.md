# Week 3 – Unsupervised Learning & Model Evaluation

YUVA Internship Project

## Objective

This project demonstrates clustering techniques, dimensionality reduction, and machine-learning model evaluation using Python and Scikit-learn.

## Topics Covered

### Unsupervised Learning
- K-Means clustering
- Hierarchical (Agglomerative) clustering
- Elbow method
- Silhouette score
- PCA dimensionality reduction

### Model Evaluation
- Train/test split
- Confusion matrix
- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC
- 5-fold cross-validation
- Hyperparameter tuning with GridSearchCV

## Datasets

- Iris dataset for clustering and PCA
- Breast Cancer Wisconsin dataset for classification evaluation

Both datasets are loaded directly from Scikit-learn, so no external dataset files are required.

## Main Results

### Clustering

| Model | Silhouette Score |
|---|---:|
| K-Means | 0.4599 |
| Hierarchical (Agglomerative) | 0.4467 |

### Logistic Regression Evaluation

| Metric | Score |
|---|---:|
| Accuracy | 0.9825 |
| Precision | 0.9861 |
| Recall | 0.9861 |
| F1 Score | 0.9861 |
| ROC-AUC | 0.9954 |

Mean 5-fold cross-validation accuracy: **0.9737**

Best hyperparameters from GridSearchCV: **{'model__C': 1, 'model__solver': 'liblinear'}**

Best cross-validation ROC-AUC during tuning: **0.9960**

## Files

- `week3_unsupervised_ml.ipynb` – complete project notebook
- `README.md` – project documentation
