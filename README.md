# AnalyticsVidhya-Black_Friday_Sales_Prediction

A simple prediction problem with very few missing data points, normally distributed data, and minimal features.  Here, I used a lightgbmregressor to make a baseline prediction, and then used hyperopt to perform bayesian optimization.  I did sparse EDA and FE to improve RMSE, but it only improved the score marginally due to few initial features to work with.

#### Best score (RMSE): 2719.43 (top ~4%)


https://datahack.analyticsvidhya.com/contest/black-friday/

A retail company “ABC Private Limited” wants to understand the customer purchase behaviour (specifically, purchase amount) against various products of different categories. They have shared purchase summary of various customers for selected high volume products from last month.
The data set also contains customer demographics (age, gender, marital status, city_type, stay_in_current_city), product details (product_id and product category) and Total purchase_amount from last month.

Now, they want to build a model to predict the purchase amount of customer against various products which will help them to create personalized offer for customers against different products.

Submissions are scored on the root mean squared error (RMSE)
