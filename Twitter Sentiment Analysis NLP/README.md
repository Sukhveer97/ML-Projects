# Twitter Sentiment Analysis
![1__JW1JaMpK_fVGld8pd1_JQ](https://user-images.githubusercontent.com/48221355/89102017-29d17180-d3fd-11ea-8cd5-236d3ef36bac.gif)


Table of Contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Model and Algorithms](#model-and-algorithms)
* [Data](#data)
* [Results](#results)

## General Info 
With this project I was able to create sentiment analysis on Twitter tweets, It will allow me to return a negative or positive analysis on the keyword(s) I specify and return either a negative or positive analysis based on those tweets mentioning the keyword(s). 

## Technologies 
* Python 3
* Google Colab 
* Visual Studio Code 

## Model and Algorithms 
* NLP 
* Sentiment Analysis 
* Twitter API (Tweepy)
* MultinomialNB
* BernoulliNB
* LogisticRegression
* SGDClassifier
* SVC
* LinearSVC
* NuSVC

## Data 
* I first create the file sentiment_mod.py which includes the model/algorithms and classifiers for this NLP using the NLTK (Natural Language Toolkit). Please view the file uploaded for the code. I first created this file in Google Colab then decided to download it as a .py file into a new environment on Visual Studio Code. 

* Below is the imports that are required, if an error rises when importing then you may have to pip install them (e.g 'pip install nltk'). Also when you import nltk, you will need to nltk.download('all'). 

![Screenshot 2020-08-01 at 8 18 59 pm](https://user-images.githubusercontent.com/48221355/89108896-73897e80-d434-11ea-940f-29178bd887f8.png)



* After this we need to create the file that will get the tweets using the Twitter API, we will also be importing the sentiment_mod.py file into this too. Please view the file upladed for the code. 
* We also need to create and sign up for a [Twitter Developers](https://developer.twitter.com/) account. Follow the steps to do this and go to your dashboard when done. Click on 'Keys and tokens', you will then be able to generate your API key and API key secret (keep these private and to yourselves only).


