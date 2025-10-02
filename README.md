# diabetes-prediction-clustering

This project was developed as part of **CS105: Data Analysis Methods** at the University of California, Riverside.
The goal was to predict diabetes outcomes using supervised machine learning models and uncover patient subgroups with clustering techniques.

---

## Project Overview

- **Data Cleaning:** Replaced biologically impossible values (e.g., 0 for Glucose, Insulin, BMI) with missing values and imputed medians.  
- **Exploratory Data Analysis (EDA):** Investigated correlations, handled missingness, and validated features.  
- **Supervised Learning:**
  - **Decision Tree:** Accuracy 69%, F1 0.53 — struggled to identify diabetic patients.  
  - **Random Forest:** Accuracy 81%, Recall 0.815, F1 0.746 — strongest overall model, prioritized recall for medical application.  
  - **Support Vector Machine (SVM):** Accuracy 74%, balanced performance but weaker recall for diabetic class.  
- **Unsupervised Learning:**
  - **K-Means Clustering:** Identified 4 patient clusters with ~67% purity vs. labeled outcomes, highlighting subgroup patterns.

---

## Key Results
- **Random Forest** outperformed other models, achieving the best balance of accuracy and recall — crucial for medical diagnostic tasks.  
- **SVM** showed solid generalization but underperformed on diabetic recall.  
- **Decision Tree** provided interpretability but weakest predictive power.  
- **K-Means** uncovered meaningful subgroups (~67% purity), though labels and clusters were not perfectly aligned.

---

## Deliverables

- [Jupyter Notebook](diabetes_prediction_clustering.ipynb) - full code and analysis
- [Python Script](diabetes_prediction_clustering.py) - raw code for quick review
- [Presentation Slides](presentation.pdf) - summary of findings

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1xV1hpPk50m4e0wb1QXWi5Eo9sG55DBWK)

---

## Tools & Libraries
- **Languages:** Python
- **Libraries:** Pandas, Scikit-learn, Matplotlib
- **Environment:** Google Colab

---

## Team
Developed by **Team 3** for CS105 (Summer 2025).
Contributors: *Joshua Ocharan, Fardin Zaman, Hana Thai, and Jonathan Li.*
