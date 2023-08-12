# User_Churn_Analysis_Modeling
- Analyze and interpret user data, generate valuable insights to help make informed business decisions.
- Develope a churn prediction model to help prevent churn, improve user retention.

## Description
- Load and inspect user data, handle missing values and outliers
- Exploratory data analysis to examine the distribution of variables and the underlying relatonships between variables
- Two sample t-test to analyze the difference in the difference in the mean amount of rides between users with two different devices
- Feature engineering
- Build and evaluate a logistic regress model
- Build and evaluate tree-based machine learning models
- Draw conclusion and insights 

- rf_cv_model.sav: a trained Random Forest cross-validation modes in binary format
- xgb_cv_model.sav: a trained XGBoost cross-validation model in binary format
- The above two files can be read into the notebook to avoid retraining the models when re-running all cells

## How to run the code
- Make sure the machine learning package(sklearn),XGBoost package are installed
- Keep commenting out the line of code where the model is fitted and the model is pickled.
