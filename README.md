# Prediction of Walmart Weather-Affected Sales 

Using the weather and Walmart sales datasets we will predict the sales of selected items in different Walmart stores for specific dates.

In this project, we will be implementing the strategy of using many different tools. We will use Jupyther Notebooks, Alteryx, MSExcel, and Tableau for data cleansing, exploratory analysis, and feature engineering. We will build and evaluate the prediction models using MS Azure.

## Problem Statement

Walmart is one of the biggest retail environments in the world, it is a great example of a successful company which implemented few important and innovative strategies throughout the years. Walmart has been keeping pace with the times, introducing the latest AI technologies into the development of processes, improvement of sales and services.
For our project we chose to study the influence of the weather conditions on the products that may be affected by the weather (umbrella, bread, etc.). Using the weather and Walmart sales datasets we will predict the sales of selected items in different Walmart stores for specific dates.
This will help to correctly predict the level of inventory needed to avoid being out-of-stock or overstock during and after special weather conditions like rain or snow storms. 

## Data

The data is taken from [Kaggle](https://www.kaggle.com/c/walmart-recruiting-sales-in-stormy-weather/overview) where Walmart created a recruiting competition.
Here is the short description of the files we will be using:

-	_key.csv_ - the relational mapping between stores and the weather stations that cover them

-	_train.csv_ - sales data for all stores & dates in the training set. The test set is unavailable so we will divide the train set and use a part of it for testing purposes. 

-	_weather.csv_ - a file containing the NOAA weather information for each station and day
