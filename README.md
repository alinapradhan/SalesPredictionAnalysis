# SalesPredictionAnalysis

Problem Statement: Predict the sales revenue of a product based on advertising expenditures across different media channels (TV, radio, and newspapers). The objective is to develop a regression model that helps businesses optimize their marketing budgets for maximum sales impact.


the notebook focuses on sales prediction using machine learning. It begins by loading the dataset 'Advertising.csv', performing data cleaning by removing unnecessary columns, handling missing values, and treating outliers using the interquartile range (IQR). Exploratory data analysis is conducted using matplotlib and seaborn. The dataset is split into training and testing sets, and preprocessing includes standardization using StandardScaler. Various regression models such as LinearRegression, Ridge, Lasso, DecisionTreeRegressor, RandomForestRegressor, SVR, and KNeighborsRegressor are trained using a pipeline approach. Hyperparameter tuning is performed using GridSearchCV, and models are evaluated based on mean_absolute_error, mean_squared_error, and r2_score. The final model is saved using joblib, ensuring reusability for future predictions.
