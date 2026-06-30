# Loan Risk Analysis using Data Engineering and Machine Learning

## Overview

This project presents a complete machine learning pipeline for loan risk analysis using real-world banking data.

The objective is to identify applicants who are suitable for loan approval by combining data engineering techniques, feature selection, supervised learning, and dimensionality reduction methods.

The project also includes a comparative study of dimensionality reduction techniques using the MNIST handwritten digit dataset.

---

## Datasets

### Loan Risk Dataset

Real-world loan application records containing demographic, financial and credit-related information.

The dataset includes more than 50 applicant attributes such as:

- Loan Amount
- Annual Income
- Debt-to-Income Ratio
- Employment Information
- Credit History
- Loan Grade
- Interest Rate
- Home Ownership
- Verification Status
- Loan Purpose

The target variable is derived from the loan grade in order to classify applicants into:

- Eligible for loan approval
- Not eligible for loan approval

---

### MNIST Dataset

The project also uses the MNIST handwritten digit dataset for dimensionality reduction experiments.

The dataset contains:

- 70,000 handwritten digits
- 28 × 28 grayscale images
- 10 digit classes

---

## Project Workflow

### Part 1 – Data Engineering

- Dataset exploration
- Data profiling
- Missing value analysis
- Statistical analysis
- Feature preprocessing
- Data visualization
- Target creation

### Part 2 – Loan Risk Classification

- Feature normalization
- Train/Test split using Stratified Sampling
- Classification model training
- Model evaluation
- Cross-validation
- Performance comparison

### Part 3 – Feature Importance

- Random Forest feature importance
- Correlation analysis
- Feature selection

### Part 4 – Dimensionality Reduction

The following techniques were evaluated on the MNIST dataset:

- Principal Component Analysis (PCA)
- Linear Discriminant Analysis (LDA)
- Uniform Manifold Approximation and Projection (UMAP)

The reduced representations were evaluated using K-Nearest Neighbors classifiers with different values of k.

---

## Machine Learning Techniques

- Data Engineering
- Feature Engineering
- Random Forest
- Classification
- Feature Selection
- PCA
- LDA
- UMAP
- K-Nearest Neighbors

---

## Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- ydata-profiling
- TensorFlow
- UMAP
- Google Colab

---

## Evaluation Metrics

Classification

- Accuracy
- Precision
- Recall
- F1-score

Dimensionality Reduction

- KNN Classification Accuracy

---

## Repository Structure

```
├── Project9_Data_Engineering.ipynb
├── bankloan.csv
├── README.md
```

---

## Key Skills Demonstrated

- Data Engineering
- Data Profiling
- Feature Engineering
- Machine Learning
- Credit Risk Analysis
- Feature Selection
- Dimensionality Reduction
- Model Evaluation
- Data Visualization

---

## Author

Georgia Takatzoglou

M.Sc. Data and Web Science

Physics Graduate | Machine Learning | Data Science
