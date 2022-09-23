# Default Prediction
A comparison of different approaches to the task of credit scoring, including:
*  Logistic regression with parameter search using Optuna
*  Gradient boosting (xgboost, lightgbm, catboost) with parameter search using Optuna
*  Random forests with parameter search using Optuna

Including several algorithms for data augmentation:
*  SMOTE
*  SVMSMOTE
*  ADASYN

And including model calibration.

Comparison done using several metrics:
* accuracy, F-score etc.
* Cohen's kappa coefficient and Matthews correlation coefficient
* Financial criteria (maximizing expected profits)


Also includes web interface for the chosen best model (deployed using Anvil)

(commentary in the notebook given in Russian)
