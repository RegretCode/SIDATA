# Tweets_Dataset_for_Sarcasm_detection_in_Hindi  
**URL**: [https://github.com/pragyakatyayan/Tweets_Dataset_for_Sarcasm_detection_in_Hindi](https://github.com/pragyakatyayan/Tweets_Dataset_for_Sarcasm_detection_in_Hindi)  

## Description  
This repository contains a raw dataset of over 16,000 tweets, including both sarcastic and non-sarcastic examples, aimed at researchers working on sarcasm detection in Hindi. The dataset includes tweets in native Hindi and is particularly focused on specific hashtags. The data was collected using a scraping script.

## Methods  
The dataset can be obtained via two methods:
1. **Scraping with Python Script**: Researchers can use the `scrap_tweets_in_Hindi-v1.py` file to rescrape tweets directly from Twitter.
2. **Download the Jupyter Notebook**: The dataset can also be downloaded and used by running the Jupyter Notebook provided in the repository.

The data collection was done using `pandas`, `tweepy`, and `textblob`.

## Results  
The dataset contains:
- **6051 Sarcastic Tweets**
- **10128 Non-Sarcastic Tweets**

The dataset spans the period from **01-01-2012 to 23-06-2020**.

## Models  
No specific models are provided in this repository. However, the dataset is meant for use in sarcasm detection models for Hindi-language tweets.

## Dataset  
The dataset includes:
- **Sarcastic tweets** (6051)
- **Non-sarcastic tweets** (10128)

Tweets were scraped using the code from Mr. Griffin Leow’s GitHub repository, with modifications to extract tweets in Hindi.
