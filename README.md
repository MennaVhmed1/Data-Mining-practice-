# Data Mining Practical Tasks

 implementations of three core Data Mining techniques applied on different datasets:

---

## 1. Classification - Titanic Survival Prediction

- **Goal:** Predict whether a passenger survived the Titanic disaster.
- **Method:** Random Forest Classifier.
- **Dataset:** Titanic passenger data.
- **Steps:**
  - Data preprocessing: mapping categorical features, handling missing values.
  - Feature selection: Age, Sex, Pclass, SibSp.
  - Train-test split and feature scaling.
  - Model training, prediction, and evaluation (accuracy & confusion matrix).
  - Visualization of feature importance.

---

## 2. Clustering - Customer Segmentation

- **Goal:** Segment mall customers based on annual income and spending score.
- **Method:** K-Means clustering.
- **Dataset:** Mall customers data.
- **Steps:**
  - Data cleaning and preparation.
  - Applying K-Means with different cluster counts.
  - Using silhouette score to find optimal number of clusters.
  - Assigning cluster labels to the dataset.

---

## 3. Association Rules - Market Basket Analysis

- **Goal:** Discover frequent itemsets and association rules in shopping data.
- **Method:** Apriori algorithm and confidence-based association rules.
- **Dataset:** Synthetic transactional data (binary encoded).
- **Steps:**
  - Create frequent itemsets with minimum support.
  - Generate association rules with minimum confidence.
  - Visualize the association rules as a directed graph.

---


## Requirements

- Python 3.x
- Libraries: pandas, scikit-learn, seaborn, matplotlib, mlxtend, networkx, numpy


