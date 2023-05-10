# Twitter Sentiment Analysis using Tweepy

This project was a part of BUAN6342 Applied natural language processing class under Prof. Gasan and focuses on analyzing sentiments of tweets related to a specific topic(We have used #chatGPT to analyze) or keyword using Tweepy, a Python library for accessing the Twitter API, and a machine learning model for sentiment classification.

## Table of Contents
- [Introduction](#introduction)
- [Requirements](#requirements)
- [Process](#process)
- [Contributers](#contributers)
- [License](#license)

## Introduction

Twitter Sentiment Analysis is the process of determining the sentiment or emotion behind tweets. This project uses Tweepy to collect tweets in real-time and applies a pre-trained sentiment analysis model to classify the tweets as positive, negative, or neutral.

Possible applications for this project include:
- Tracking public sentiment on a specific topic or event
- Analyzing customer feedback about products or services
- Monitoring public opinions on political campaigns or social issues

## Requirements

- Python 3.9
- Tweepy API
- VADER sentiment analysis model 
- Twitter Developer Account and API credentials (API Key, API Secret Key, Access Token, and Access Token Secret)- This is paid and costed about $100 to run 10,000 tweets!

## Process
## 1. Import packages and load the data
## 2. Data cleaning-
  A. About the data:
     <img width="560" alt="image" src="https://github.com/vmk9/Twitter-sentiment-analysis-using-NLP/assets/106167638/7de6e6ca-2d9d-4b6a-ab75-6ee5b96e7059">
     
  B. data cleaning steps:
     <img width="556" alt="image" src="https://github.com/vmk9/Twitter-sentiment-analysis-using-NLP/assets/106167638/e8f7f735-3acb-4862-9f00-57b27a6b2107">
     
  C. Cleaned data output:
     <img width="564" alt="image" src="https://github.com/vmk9/Twitter-sentiment-analysis-using-NLP/assets/106167638/27c434fc-ae46-45ff-97c9-73f4083f8670">

## 3. Sentiment analysis using VADER:
   The sentiment of each tweet is generated by looking at the compound score and then it classifies into positive, negative and neutral. 
    <img width="776" alt="image" src="https://github.com/vmk9/Twitter-sentiment-analysis-using-NLP/assets/106167638/b2cf87d2-5583-49fc-bad9-1aa49765a329">

## 4. Data exploration:
   <img width="260" alt="image" src="https://github.com/vmk9/Twitter-sentiment-analysis-using-NLP/assets/106167638/ddfd29db-6b7a-4896-9a0f-704c919b3593">
   
## 5. Topic modelling:
  <img width="541" alt="image" src="https://github.com/vmk9/Twitter-sentiment-analysis-using-NLP/assets/106167638/812a9299-c919-4550-8005-1403678ff695">
  
   ![image](https://github.com/vmk9/Twitter-sentiment-analysis-using-NLP/assets/106167638/bfc15788-a5bf-4f3b-af16-78858ca38b79)


## Contributers
1. Vamsi krishna kanderi murali- Project Lead
2. sikhi yalavarthi
3. Azimi bijan

## Conclusion

## 1.Overall people feel positive about chatGPT on twitter
## 2.Cyber Security has the least positive tweets
## 3.ChatGPT is being used for things such as engineering, shopping, and just general questions


