# Engage2Value-IITM-Machine-Learning-Project
This project is part of the Engage2Value: From Clicks to Conversions competition. The goal is to predict a customer’s purchase value based on their multi-session behavior across digital touchpoints.

Using a dataset of anonymized user interactions (browser types, traffic sources, device details, geographical indicators, etc.), the project applies advanced feature engineering and machine learning models (XGBoost, RandomForest, HistGradientBoosting, Ridge) to estimate purchase potential.

The pipeline includes:

* Cleaning and transforming raw clickstream data

* Handling high-cardinality categorical features with target encoding

* Creating meaningful features like engagement ratios and session-level indicators

* Hyperparameter tuning to improve predictive performance

The model achieved a strong performance on Kaggle, with an R² score close to 0.70+ on the leaderboard.
