# BigMart_Sales_Prediction
Python | Machine Learning | Jupyter Notebook <br> <br>
This project aims to build a predictive model to find out the sales of each product at a particular store. BigMart has collected 2013 sales data for 1559 products across 10 stores in different cities. The goal is to understand the properties of products and stores which play a crucial role in increasing sales.

●	Executed detailed Exploratory Data Analysis (EDA) and data cleaning on a dataset of 8,500+ rows, accurately treating missing values and Performed advanced Feature Engineering to improve model depth. <br>
●	Implemented and evaluated multiple models, including Linear Regression, Decision Trees, and Ensembles, utilizing Grid Search for hyperparameter tuning to minimize RMSE and identify key sales drivers. <br>


### Used packages:
numpy <br>
pandas <br>
matplotlib <br>
seaborn <br>

### Exploratory Data Analysis (EDA) :<br>
Analyzed distribution of Item MRP, Outlet Type, and Item Visibility.

### Data Preprocessing :<br>
1.Handled missing values in Item_Weight and Outlet_Size.<br>
2.Corrected Item_Visibility (handled 0.0 values using mean imputation).<br>
3.Fixed inconsistent labels in Item_Fat_Content (Low Fat vs LF).<br>

### Feature Engineering :<br>
1. Created Outlet_Age from the establishment year.<br>
2. Derived broad categories for Item_Type (Food, Drinks, Non-Consumable).<br>

### Used models:
Linear_Regression <br>
Decision_Tree Regressor <br>
Bagging using GridSearch <br>
Random_Forest Regressor <br>

### Evaluation metrics:
Mean Squared Error <br>
Root Mean Squared Error <br>
Mean Absolute Error <br>
R square <br>
