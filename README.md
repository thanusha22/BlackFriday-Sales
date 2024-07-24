# Product Recommendation System

In the contemporary competitive marketplace, organizations are endeavouring to maximize their profits and 
revenue through the implementation of personalized product recommendations to their customers. To 
achieve this, it is imperative to gain an in-depth comprehension of the purchasing patterns of customers and 
identify the demographic factors that impact their purchasing behaviour. This research project focuses on 
a meticulous analysis of customer demographic and purchasing data to unearth underlying patterns and 
forecast purchase amounts with precision. Through the utilization of advanced machine learning models, 
the study aims to ascertain the optimal approach to recommending products to customers, based on specific 
demographics, such as age, gender, occupation, marital status, and city of residence. With this intelligence, 
businesses can enhance customer experience by delivering tailored recommendations, which can, in turn, 
bolster profits and revenue. The insights derived from this study will enable businesses to adapt their 
product recommendation strategies effectively to better address the requirements of their clientele and 
achieve a competitive edge in the marketplace. 

Introduction : 
Black Friday is an eagerly awaited shopping extravaganza, occurring annually on the day following 
Thanksgiving in the United States. This event is synonymous with unparalleled deals, significant discounts, 
and lengthy queues of eager shoppers. Given its potential to substantially impact revenue and profits for 
the entire year, Black Friday has emerged as a critical day for retailers. In recent years, this day has evolved 
beyond its American origins, becoming a global phenomenon, with retailers worldwide offering discounts 
and promotions to attract customers. As one of the most significant shopping events of the year, Black 
Friday is of tremendous interest to the retail industry. 
Against this backdrop, this project aims to analyze the best model and predict purchase amounts. 
Subsequently, this information will guide organizations in recommending products to purchase, focusing 
on specific demographics such as age, gender, occupation, marital status, and city, with the objective of 
maximizing profits and revenue. To this end, the project has analyzed over half a million rows for Black 
Friday sales, employing an extensive analysis of four distinct models, including linear regression, XG boost, 
decision tree, and random forest. Prior to modelling, data cleaning was conducted, involving the removal 
of missing values, data transformation, and data visualization.


Data Source: 
The Black Friday Sales data set is taken from Kaggle. 
Kaggle link: https://www.kaggle.com/datasets/pranavuikey/black-friday-sales-eda 

Data Description: 
This data set has 12 columns and 550, 069 rows. Below are the columns present in this data set. 
1. User Id - Customer User Id 
2. Product Id - Unique Id for Product 
3. Gender - Sex of Customer 
4. Age - Age of Customer 
5. Occupation - Occupation code of Customer 
6. City_Category - City of Customer 
7. Stay_In_Current_City_Years - Number of years of stay in city 
8. Marital_Status - Marital Status of customer 
9. Product_Category_1 - Category of Product 
10. Product_Category_2 - Category of Product 
11. Product_Category_3 - Category of Product 
12. Purchase - Purchase Amount 
Purchase is the target variable. There are 4 continuous variables and 8 categorical variables.

Models Evaluated: 
1. Linear Regression
2. Decision Tree Regression
3. Random Forest Regression (Best Performance: Accuracy of 86%)
4. XGBoost Regression


Key Findings
The Random Forest model was the most effective, providing an accuracy of 86%.
Customer demographics significantly influence purchasing patterns, with features like occupation and product category showing strong correlations with purchase amounts.

Dependencies
Python 3.8+
pandas
numpy
scikit-learn
xgboost
matplotlib
seaborn

REFERENCES 
1. https://www.kaggle.com/datasets/pranavuikey/black-friday-sales-eda 
2. https://ieeexplore.ieee.org/xpl/conhome/9396768/proceeding 
3. https://github.com/nanthasnk/Black-Friday-Sales-Prediction 
4. https://medium.com/@1512aliahmad/black-friday-sales-prediction-cd477ebae018
