# Data Science Portfolio

This repository collects selected data science and machine learning projects, with a focus on structured analysis, model comparison, and interpretability.

## Projects

### 1. Explainable Insurance Purchase Prediction
- Binary classification using socio-economic and demographic data  
- Comparison of multiple model families (logistic regression, decision tree, random forest, gradient boosting)  
- XGBoost selected as the primary model based on ROC-AUC  
- Global and local explainability using SHAP  

Repository: https://github.com/m-zhokhova/explainable-insurance-purchase-prediction

---

### 2. Subjective Wine Ratings Analysis
- Exploratory data analysis of expert wine ratings with subjective targets  
- Clustering based on numerical features (price, age, alcohol) versus categorical composition (grapes, region, producer)  
- Supervised modeling using linear regression, random forest, and gradient boosting  
- Comparison of numerical-only, categorical-only, and combined feature sets  
- Explainability with SHAP to assess global and local feature contributions  
- Case study on feature relevance, model limits, and low-signal datasets  

Repository: https://github.com/m-zhokhova/subjective-wine-ratings-analysis

---
### 3. Explainable Hospital Length of Stay Prediction (MIMIC-III)

- Regression and classification of hospital LOS using demo-scale MIMIC-III data  
- Honest evaluation under weak signal (R² ≈ 0)  
- Logistic regression selected for interpretability and stability  
- Explainability via coefficients, intercept bias, and local decomposition  
- Case study on class imbalance and care pathway effects  

Repository: https://github.com/m-zhokhova/hospital-los-prediction
