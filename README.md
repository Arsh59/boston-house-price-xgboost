This project predicts the median house prices (MEDV) in Boston using machine learning, with a focus on clean pipelines and model accuracy. The dataset from Kaggle includes features like crime rate, number of rooms, tax rate, and distance to employment hubs.

After data cleaning and EDA, new features such as TAX_PER_ROOM and AGE_CAT were engineered. A preprocessing pipeline was built using StandardScaler and OneHotEncoding to streamline transformations.

Multiple models were tested: Linear Regression, Random Forest, and XGBoost. The final model, XGBoost, was trained using a log-transformed target for better stability. Hyperparameters were tuned using GridSearchCV, and cross-validation was applied for robust performance evaluation.

XGBoost achieved an RMSE of ~3.83 and an R² score of ~0.89. Visualizations confirmed strong prediction accuracy, with most predictions aligning well with actual values. Key features influencing the model were LSTAT, RM, and TAX_PER_ROOM.

This end-to-end regression project demonstrates practical skills in data preprocessing, feature engineering, model tuning, and evaluation using Python, scikit-learn, and XGBoost.



