# Netflix Subscription Plan Predictive Analysis

The dataset consists of the following columns:
1. User ID: Unique identifier for the user.
2. Subscription Type: Type of subscription (Basic, Standard, Premium).
3. Monthly Revenue: Revenue generated per month.
4. Join Date: Date when the user joined.
5. Last Payment Date: Date of the last payment.
6. Country: Country of the user.
7. Age: Age of the user.
8. Gender: Gender of the user.
9. Device: Device used by the user.
10. Plan Duration: Duration of the plan.

**A. Linear Regression model ​​**

The Linear Regression model has the following performance metrics:

1. Mean Squared Error (MSE): 2.82
2. R-squared (R²): -0.02

The negative R-squared indicates that the model does not fit the data well. Let's try a more complex model like Random Forest Regressor.

**B. Random Forest Regressor**

The Random Forest Regressor model has the following performance metrics:

1. Mean Squared Error (MSE): 3.41
2. R-squared (R²): -0.24
   
The performance of the Random Forest Regressor is also not satisfactory. Let's try the Gradient Boosting Regressor next.

**C. Gradient Boosting Regressor**

The Gradient Boosting Regressor model has the following performance metrics:

1. Mean Squared Error (MSE): 2.87
2. R-squared (R²): -0.04

None of the models are performing well, indicated by negative R-squared values. This suggests that the features selected may not be sufficient to predict the monthly revenue accurately.

**Conclusion**

The current features and models are not yielding good results. It may be beneficial to:

1. Explore more features or derived features (e.g., interaction terms, more granular time features).
2. Perform more in-depth feature selection.
3. Experiment with other machine learning models or ensembles.
4. Possibly use external data sources to enrich the dataset.




