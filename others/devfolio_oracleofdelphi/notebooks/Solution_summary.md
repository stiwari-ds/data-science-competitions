# Approach:
**[Notebook mentioned in each step]**

1. Data visualization to explore features and remove outliers. **[00-eda-baseline]**
2. Dimensionality reduction through feature selection methods -   
Mutual Information Score, ANOVA F-test, Kendall-Tau correlation **[00-eda-baseline]**
4. Testing performance of reduced features sets as well as original vs. outlier-clipped dataset using a simple model (scikit-learn ExtraTreesClassifier) **[00-eda-baseline]**
5. Tuning XGBoost using Optuna. **[01-xgboost]**
6. Tuning LightGBM using Optuna. **[02-lightgbm]**
7. Final submission file generated. **[03-final-solution]**

# Summary: 
* Reduced feature set based on ANOVA F-test performed better than complete feature set. Accuracy is gained along with improvement in performance and reduction in model complexity.
* XGBoost performed best out of the models used in the experiments.
* Final submission file is generated using tuned hyperparameters from notebook **01-xgboost** and 5-fold cross validation.
