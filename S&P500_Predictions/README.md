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

* First you must install and import yfinance 
![Screenshot 2020-07-10 at 2 49 15 pm](https://user-images.githubusercontent.com/48221355/87161680-c734fc00-c2bc-11ea-9fd2-16e9b3954c30.png)


* Parsing data from Wikipedia
![Screenshot 2020-07-10 at 2 37 53 pm](https://user-images.githubusercontent.com/48221355/87160817-7b358780-c2bb-11ea-82a5-967b2b8cb4c5.png)

* Parsing data from Yahoo Finance and storing them in my Google Drive
![Screenshot 2020-07-10 at 2 39 00 pm](https://user-images.githubusercontent.com/48221355/87161886-0cf1c480-c2bd-11ea-9d34-0ebab4c71f25.png)


