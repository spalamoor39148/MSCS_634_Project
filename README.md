# Health Data Mining Project

## Dataset Summary
The project uses a health-related dataset with over 500 patient records and 10+ clinical attributes, including age, cholesterol, blood pressure, and heart rate. The dataset is suited for predictive modeling of cardiovascular disease risk due to its comprehensive and relevant features.

## Project Steps
1. **Data Preparation:**  
   Cleaned data by handling missing values, removing duplicates, and correcting inconsistencies. Performed exploratory data analysis (EDA) to understand distributions, detect outliers, and identify feature correlations.

2. **Feature Engineering:**  
   Created new features from existing data, normalized numeric features, and selected important variables based on statistical analysis and model feedback.

3. **Modeling:**  
   Built regression models to predict clinical outcomes and classification models (Decision Tree and SVM with hyperparameter tuning) to predict disease presence. Applied K-Means clustering to segment patients. Used Apriori algorithm for association rule mining.

4. **Evaluation:**  
   Compared classification models using accuracy, F1-score, confusion matrices, and ROC curves. Evaluated clustering through visualization and association rules through confidence and lift metrics.

## Major Findings
- Decision Tree outperformed SVM in classification accuracy (77% vs 72%).  
- Clustering revealed meaningful patient subgroups potentially representing different risk profiles.  
- Association rules identified frequent co-occurrence of hypertension, high cholesterol, and age-related risk factors.  
- Ethical considerations included data privacy, bias assessment, and model transparency to ensure responsible AI use.

---

This project highlights the value of combining multiple data mining techniques to support healthcare insights and decision-making.
