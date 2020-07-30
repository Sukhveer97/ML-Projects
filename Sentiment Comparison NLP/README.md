# Sentiment Comparison 
![1_PGB0w1JZslqA-hM0xGrmJw](https://user-images.githubusercontent.com/48221355/88963569-f0372400-d29f-11ea-801a-29d3a11c002c.gif)


This is a very small and quick introduction piece I looked into when starting NLP. 

## Table of Contents 
* [General info](#general-info)
* [Technologies](#technologies)
* [Model and Algorithms](#model-and-algorithms)
* [Data](#data)
* [Results](#results)

## General Info 
Using NLP (Natural Language Processing) with a Twitter API to build a sentiment comparison program using tweets in real time. 

## Technologies 
* Python 3
* Visual Studio Code

## Model and Algorithms 
* NLP 
* Twitter API (Tweepy)
* TextBlob 
* Sentiment comparison 

## Data 
* First we need to create a virtual environment in VS Code 
![ezgif com-video-to-gif](https://user-images.githubusercontent.com/48221355/88970573-8f611900-d2aa-11ea-9aed-e8ad55dfff83.gif)


* We then need to create a .py file, you can call this whatever you would like (for me it was 'world_sentiment_.py') and import the necessary libraries and modules 
* If you come across an issue importing these modules then you may need to use the terminal to then 'pip install tweepy'. 
<img width="521" alt="Screenshot 2020-07-30 at 9 23 27 pm" src="https://user-images.githubusercontent.com/48221355/88970936-18785000-d2ab-11ea-9cdf-996cbfa1f661.png">

* View the world_sentiment_.py file to see the rest of the code

* We now need to create and sign up for a [Twitter Developers](https://developer.twitter.com/) account. Follow the steps to do this and go to your dashboard when done. Click on 'Keys and toekns', you will then be able to generate your API Key and API key secret (keep these private and to yourselves only). 

* Now create another .py file called 'secrets.py', in this you will be storing your API Key and API key secret. 
<img width="277" alt="Screenshot 2020-07-30 at 9 44 24 pm" src="https://user-images.githubusercontent.com/48221355/88972784-fd5b0f80-d2ad-11ea-8bba-57db941217ba.png">


