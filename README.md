# Dry Bean Classification and Clustering Analysis

## Overview

In this project I am just messing around and exploring diffrent clasification and clustering models. I explore supervised and unsupervised machine learning techniques on the Dry Bean Dataset. The analysis includes data preprocessing, exploratory data analysis (EDA), classification, clustering, dimensionality reduction, and model evaluation.

The goal is to compare multiple machine learning approaches and analyze their effectiveness for bean type classification and cluster discovery.

---

## Dataset

 Dry Bean Dataset contains features extracted from images of dry beans belonging to multiple classes.

Features include:
- Area
- Perimeter
- Major Axis Length
- Minor Axis Length
- Compactness
- Shape related measurements

Target:
- Bean class/type

---

## Project Objectives

- Perform exploratory data analysis (EDA)
- Preprocess and normalize the dataset
- Apply supervised learning algorithms
- Apply unsupervised clustering algorithms
- Compare model performance using multiple evaluation metrics
- Analyze clustering behavior before and after dimensionality reduction

---

## Machine Learning Models

### Supervised Learning
- K-Nearest Neighbors (KNN)
- Random Forest
- Naive Bayes

### Unsupervised Learning
- K-Means
- DBSCAN
- PAM / K-Medoids

---

## Techniques Used

- Feature scaling
- Correlation analysis
- Principal Component Analysis (PCA)
- Hyperparameter experimentation
- Model comparison
- Cluster visualization

---

## Evaluation Metrics

### Classification Metrics
- Accuracy
- Precision
- Recall
- F1-score

### Clustering Metrics
- Silhouette Score
- Adjusted Rand Index (ARI)
- Normalized Mutual Information (NMI)
- Purity Score

---

## Key Findings

- Random Forest and KNN achieved strong classification performance on the dataset.
- DBSCAN struggled in high-dimensional space and I tried experimentation with PCA preprocessing.
- PCA helped improve cluster separability and with visualization.

---

## Repository Structure

```text
dry-bean-ml-analysis/
│
├── README.md
├── requirements.txt
├── .gitignore
│
├── notebooks/
│   └── dry_bean_classification_and_clustering.ipynb
│
├── results/
│
└── data/
```

---


## Future Improvements

- Experiment with additional ensemble methods
- Apply advanced dimensionality reduction techniques
- Improve clustering optimization
- Explore deep learning approaches for classification

---

## Tools & Libraries

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook