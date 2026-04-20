🏠 House Price Prediction | End-to-End Machine Learning Pipeline
🚀 Project Summary

Built a production-ready ML pipeline to predict house prices using structured data.
Focused on data preprocessing, model comparison, and hyperparameter tuning to achieve strong predictive performance.

🎯 Key Results
📈 R² Score: 0.82+ (explains 82% variance)
📉 Reduced prediction error using advanced ensemble models
⚡ Improved performance via hyperparameter tuning (GridSearchCV)

🧠 Skills Demonstrated
Data Preprocessing (Missing Values, Encoding, Scaling)
Feature Engineering & EDA
Model Selection & Evaluation
Cross-Validation Techniques
Hyperparameter Tuning
Pipeline Building (Production-style ML workflow)

🔍 Approach
1. Data Processing
Handled missing values using SimpleImputer
Scaled numerical features using StandardScaler
Encoded categorical variables using OneHotEncoder
Used ColumnTransformer for structured preprocessing

2. Model Development

Evaluated multiple models:

Linear Regression
Ridge & Lasso
Random Forest Regressor
HistGradientBoostingRegressor (Best Performer)


3. Model Evaluation

Used robust metrics:

RMSE (penalizes large errors)
MAE (average error)
R² Score (model explainability)

Applied cross-validation for reliable performance estimation.

4. Hyperparameter Tuning
Implemented GridSearchCV
Optimized key parameters:
learning_rate
max_depth
max_leaf_nodes
regularization

🏆 Final Model
Selected HistGradientBoostingRegressor
Built end-to-end Pipeline (Preprocessing + Model)
Ensures:
No data leakage
Scalable and reusable workflow
