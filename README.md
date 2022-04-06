# Machine-Learning
	New York City Taxi fare prediction 

**Description:** In this project, we're looking to predict the fare for the New York city's taxi future transactional cases. Taxis delivers service to lakhs of customers daily. Now it becomes really important to manage their data properly to come up with new business ideas to get best results. Eventually, it becomes really important to estimate the fare prices accurately.

This dataset is referred from Kaggle.
The datset contains the following fields:

➡ key - Unique ID field. (Not necessarily needed in the training set)

➡ fare_amount - the cost of each trip in USD

➡ pickup_datetime - date and time when the meter was engaged

➡ passenger_count - the number of passengers in the vehicle

➡ pickup_longitude - the longitude where the meter was engaged

➡ pickup_latitude - the latitude where the meter was engaged

➡ dropoff_longitude - the longitude where the meter was disengaged

➡ dropoff_latitude - the latitude where the meter was disengaged

➡ pickup_datetime - timestamp value indicating when the taxi ride started

This is a Supervised Learning regression problem.

**Key skills:** Data Cleaning, Feature Engineering, EDA, Visualization, Hyperparameter tuning, Multiple Linear Regression, Random Forest, XGBoost, Ridge & Lasso Regression.

**Project Outcomes:**
XGBoost Regressor & Lasso Regressor (Before & After the hyperparameter tuning) cannot be considered due to higher RMSE scores.

Ridge Regressor (After hyperparameter tuning) gives slightly higher RMSE scores. So we can think of Ridge Regressor (Before hyperparameter tuning)

Therefore, Multiple Linear Regressor & Ridge Regressor with the default parameter settings can be considered as a better fit model because of lesser RMSE scores as compared to other models.
