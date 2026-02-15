# Advanced Statistical Learning & Classification Projects

This repository features advanced statistical analyses focused on **Machine Learning**, specifically addressing binary classification challenges and unsupervised clustering for complex, non-standard data distributions.

## Project Overview

The repository is organized into two primary analytical studies:

### 1. Comparison of Supervised Classification Methods
This project conducts a rigorous comparative analysis to identify the most effective predictive model for binary targets. It evaluates the trade-off between model interpretability and predictive power across various statistical and machine learning frameworks.

**Techniques & Models Implemented:**
* **Logistic Regression:** Established as the baseline model for binary classification.
* **Lasso & Ridge Regularization:** Applied to logistic regression to handle multicollinearity and perform automated variable selection.
* **Generalized Additive Models (GAM):** Utilizing a logistic link function and smoothing splines to capture non-linear relationships between predictors and the target.
* **Random Forest:** An ensemble bagging technique used to model complex feature interactions and ensure robustness.
* **XGBoost:** An optimized Gradient Boosting implementation designed to maximize predictive accuracy through iterative error correction.

### 2. Non-Gaussian Data: Unsupervised Clustering
This study explores clustering methodologies for datasets that violate the assumption of normality. In real-world scenarios, data often exhibit heavy tails, skewness, or outliers—conditions where standard algorithms like K-means or traditional Gaussian Mixture Models (GMM) often underperform.

**Technical Focus:**
* **Generalized Hyperbolic Distributions:** Implementation of flexible probability distributions to better capture the underlying latent structure of the data.
* **Teigen Model:** Application of clustering models based on the multivariate t-distribution to manage heavy-tailed data.
* **Box-Cox Transformations:** Tested as a preprocessing step to normalize data, though findings suggest that flexible distribution models often provide superior results without transformation.
* **Model Selection:** Use of **ICL** (Integrated Classification Likelihood) and **BIC** (Bayesian Information Criterion) to determine the optimal number of clusters.

---

## Technology Stack
* **Language:** R
* **Environment:** RMarkdown

---
**Author:** Carmela Uccello  
**Date:** January 2026
