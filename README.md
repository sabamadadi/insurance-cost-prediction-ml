# Predicting Insurance Policy Costs Using Machine Learning

[Kaggle Competitions](https://www.kaggle.com/competitions/data-science-5-sbu/leaderboard) Fifth score (1.0946213014)

[Full Report](https://drive.google.com/file/d/1Cf21G0ubgu8sm_Y_j2p2E1bngO8KpD2U/view?usp=sharing)

---

## Overview
This project focuses on predicting insurance policy costs using machine learning techniques. It covers data preprocessing, exploratory data analysis (EDA), feature engineering, and predictive modeling.

---

## Dataset
- Numerical, categorical, and temporal features
- Skewed target variable (policy cost)
- Log-transformation applied for stability

---

## Methodology
1. **Preprocessing**
   - Imputation of missing values
   - Scaling of numeric features
   - Encoding categorical variables (one-hot & target encoding)
2. **Feature Engineering**
   - Temporal features (policy start date, age)
   - Interaction terms (earnings × dependents)
   - Log-transformations and binning for skewed variables
3. **Modeling**
   - Ridge Regression and Elastic Net as primary models
   - Hyperparameter tuning using cross-validation
   - Evaluation metric: RMSLE

---

## Key Findings
- Temporal and interaction features improve model accuracy
- Regularized linear models perform well on engineered features
- Log transformation stabilizes variance and reduces RMSLE
- Careful categorical encoding avoids data leakage

---

## Future Work
- Explore tree-based ensembles and gradient boosting
- Implement stacking of linear and nonlinear models
- Incorporate external macroeconomic indicators

---

## Conclusion
A robust and interpretable pipeline was developed for insurance cost prediction. The combination of preprocessing, feature engineering, and regularized regression provides a reliable foundation for actuarial modeling.
