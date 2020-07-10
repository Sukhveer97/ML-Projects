# S&P 500 Stock Predictions

## Table of contents 
* [General info](#general-info)
* [Technologies](#technologies)
* [Model and Algorithms](#model-and-algorithms)
* [Data](#data)

## General info 
Acquiring my own data by scraping data from yahoo finance on the S&P 500 to predict(with a confidence % output) the next n days with a set % stock change parameter which will tell me whether to buy, sell or hold stocks. 

## Technologies 
Python 3.6 on Google Colab connected to Python 3 Google Compute Engine Backend

## Model and Algorithms
* Time-series/prediction model
* Linear SVC(Support Vector Classifier)
* KNeighbors
* Random Forest
* SVC using OvO(OneVsOne multiclass Classifier)

## Data
Dataset was scraped from two websites, [Wikipedia](https://en.wikipedia.org/wiki/List_of_S%26P_500_companies) and [Yahoo Finance](https://uk.finance.yahoo.com/) using the Beautiful Soup Python parsing package. 

* Parsing Data from Wikipedia
