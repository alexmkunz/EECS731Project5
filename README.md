# EECS 731 Project 5: Order Demand Prediction
Use time series information, product type, warehouse location, and product category to predict order demand.

## Data Set
**Historical Product Demand.csv**: Order demand for different products, categories, and warehouses over time.

## Juypter Notebook
**wordWideProductsInc.ipynb**:
 - **Exploratory Data Analysis:** explore order demand vs. date for the entire data set, categories, products, and warehouses.
 - **Feature Engineering:** create an outlier-free Dataframe and encode product, category, and warehouse columns.
 - **Regression Models:** compare accuracy of linear and gradient boosting regression models when trained on the original data set and the outlier-free data set.
