# Insurance-Premium-Prediction-using-Machine-Learning
This project builds and evaluates machine learning models to predict insurance premiums based on customer attributes. The dataset includes variables such as age, income, health score, credit score, policy details, and claims history.

Key steps:

Data Preprocessing: Handled missing values, outliers, and skewed features using transformations (log, Box-Cox), encoding, and binning.

Exploratory Data Analysis (EDA): Identified feature distributions, correlations, and insights using visualizations.

Feature Engineering & Selection: Applied recursive feature elimination (RFE) and importance ranking to select relevant predictors.

Model Development: Built and compared models including Linear Regression, Decision Tree, Random Forest, and XGBoost.

Hyperparameter Tuning: Used RandomizedSearchCV to optimize model parameters.

Evaluation: Assessed models using Root Mean Squared Logarithmic Error (RMSLE), achieving best performance with XGBoost (RMSLE: 0.4653).

Final deliverables include a trained predictive model, insights into key predictors (Credit Score, Previous Claims, Annual Income), and recommendations for insurance pricing strategies.

Repository contains Jupyter notebooks, scripts, documentation, and results.
