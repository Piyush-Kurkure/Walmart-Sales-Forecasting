# Walmart-Sales-Forecasting

Aim - Estimate the unit sales of Walmart retail goods

Dataset: We are predicting item sales at stores in various locations for two 28-day periods. (i.e d_1914 - d_1970)
- calendar.csv - Contains information about the dates on which the products are sold.
- sales_train_validation.csv - Contains the historical daily unit sales data per product and store [d_1 - d_1913]
- sell_prices.csv - Contains information about the price of the products sold per store and date.

The dataset involves the unit sales of 3,049 products, classified in 3 product categories (Hobbies, Foods, and Household) and 7 product departments, in which the categories are disaggregated.  The products are sold across ten stores, located in three States (CA, TX, and WI).

<img src='https://i.imgur.com/Ae5QBi9.png' style="width:500px;height:300px;">

This project comprises of two parts:

Data Analysis
Machine Learning Model for Forecasting
In the Data Analysis part, the exploration of trends in the data is done across different stores, items, dates, regions, etc. The distribution of items is analyzed by comparing them with each other. Various procedures for Signal Denoising is also researched to study the signal pattern.

In the Machine Learning part, Feature Learning is performed so that every category is converted into a machine-readable format. Some extra features are also added to data since the data is about trends of sales across the time period. The model used here is Keras Neural Network which is designed from various layers of embedding of the input layers.
