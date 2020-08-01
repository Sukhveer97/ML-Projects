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



* After this we need to create the file that will get the tweets using the Twitter API, we will also be importing the sentiment_mod.py file into this too. Please view the file upladed for the code called twitter.py. 
* Below is the imports that are required, if an error rises when importing then you may have to pip install them (e.g 'pip install tweepy')

![Screenshot 2020-08-01 at 8 41 43 pm](https://user-images.githubusercontent.com/48221355/89109271-949f9e80-d437-11ea-9466-4d35e6fcc60b.png)


* We also need to create and sign up for a [Twitter Developers](https://developer.twitter.com/) account. Follow the steps to do this and go to your dashboard when done. Click on 'Keys and tokens', you will then be able to generate your API Key, API Key Secret, Access Token & Access Secret (keep these private and to yourselves only).
* Once we have our keys and tokens we will then create a seperate .py file which will contain these, in the twitter.py file I have imported everything in from a file called secrets.

![Screenshot 2020-08-01 at 8 46 50 pm](https://user-images.githubusercontent.com/48221355/89109366-72f2e700-d438-11ea-9925-1d25c25a2763.png)

* Below is a screeshot of how to import both the secrets and sentiment_mod files into the twitter.py file. 

![Screenshot 2020-08-01 at 8 51 58 pm](https://user-images.githubusercontent.com/48221355/89109443-1a701980-d439-11ea-84c0-670316df10bf.png)

* The final step is to create the visualisations of the analysis, which is optional but I believe it will give us a better understanding. 
* For this we create a seperate .py file, I named it as graph.py and below are the required imports


<img width="429" alt="Screenshot 2020-08-01 at 10 24 20 pm" src="https://user-images.githubusercontent.com/48221355/89110751-cfa8ce80-d445-11ea-96d5-5807faea3c89.png">


* 

