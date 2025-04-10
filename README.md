# Capstone-Bitcoin-Price-Prediction

## Capstone Project. M.S. Data Analytics

Bukola Adeniyan, [Github](https://github.com/Queensdelight/Capstone-Bitcoin-Price-Prediction)

## Introduction
This project explores one potential driver of this volatility—public sentiment toward Bitcoin. Using sentiment analysis on Twitter, the study examines whether there is a correlation between Bitcoin’s market value and the overall sentiment expressed in tweets.

## How to Install and Run the Project
**1. Create a new project repository in Github, copy the repository URL, then clone to your machine:**
```bash
git clone project.url
```

**2. Verify Python version of Python 3:**
Windows: 
```shell
py --version
```
If Python 3 is not installed, install it before proceeding.


**3. Create your .venv and activate it.**
Windows: 
```shell
py -3.11 -m venv .venv
.venv\Scripts\activate
```


**4. Install the required dependencies:**
Windows: 
```shell
py -m pip install jupyterlab pandas matplotlib scikit-learn numpy seaborn
py -m pip install --upgrade scikit-learn
```

## 📦 Tech stack & packages used 

|package|usage case|
|---|---|
|Python| Python served as the backbone of my project, allowing me to leverage its versatility and extensive libraries to create robust and efficient code.|
|Pandas| The Pandas Python library facilitated data handling, transformation, and analysis, allowing me to extract valuable insights and make informed decisions about the datasets.|
|Matplotlib|  The Matplotlib Python library allowed me to generate informative graphs, charts, and plots, enhancing the presentation and understanding of the data analysis results.|
|Keras|  The Keras Python library was used to implement the LTSM deep-learning approach to sentiment analysis.|
|Sklearn (Scikit Learn)| The Sklearn Python library allowed me to implement the machine learning sentiment analysis approach, and produce a preprocessing pipeline.|
|NLTK (Natural Language Toolkit)| The NLTK Python module has facilitated the datasets' preprocessing.|


## :dart: Project Objectives

- [x] Explore methods for and carry out scraping of Bitcoin-related tweets

> As the sentiment analysis portion of the project heavily relies on having tweets to analyse the sentiment of, I will need to acquire a large dataset of Bitcoin-related tweets. Researching how to scrape the relevant tweets from twitter and building the initial dataset is the first step in completing the project.
As I am aiming to compare sentiment over time to the value over time, I will need to decide on a time-period that I will scrape both the tweets and Bitcoin value data over.

- [x] Research and apply necessary pre-processing techniques to the dataset of tweets

> Due to the noisy nature of tweets, carrying out pre-processing techniques is crucial for ensuring the sentiment analysis is as accurate as possible. Similar to how numerical datasets are often normalised in machine learning to prevent bias, pre-processing the tweets will prevent any bias when determining their sentiment.

- [x] Investigate and evaluate the performance of different sentiment analysis methods}

> Researching and comparing different sentiment analysis methods, as opposed to arbitrarily selecting a single technique, is crucial to achieving the highest degree of accuracy when evaluating the sentiment towards Bitcoin. 

- [x] Apply the most accurate sentiment analysis method to the dataset of Bitcoin-related tweets

>  After having determined the sentiment analysis method that will result in the highest accuracy, and therefore the most accurate conclusion, I need to apply it to the dataset of Bitcoin-related tweets to determine the sentiment of each tweet.   

- [x] Find the general sentiment of tweets for each day, as well the general sentiment of a select subsample of the most popular tweets

>  Not only does this project aim to find a correlation between the sentiment of Bitcoin related tweets and its value, it also aims to find out if the popularity of these tweets has an influence on this correlation. To meet both aims I will need to find the average sentiment for all tweets posted on the same day, and a separate average for only those tweets which have over a certain level of popularity.

- [x] Acquire relevant market data for the Bitcoin cryptocurrency

>  To facilitate a comparison between Bitcoin’s sentiment and its value, I will need to acquire the market data for Bitcoin. As the comparison between sentiment and value is being made over time, the data must be from the same time-period as the tweets collected.

- [x] Produce a time-series visualisation comparing overall sentiment towards Bitcoin for each day, the sentiment of the most popular tweets for each day, and Bitcoins daily value

>   Visualising the data on a single time-series is an effective method to analyse the data and discover if there is any correlation between the sentiment towards Bitcoin and its value.

- [x] Evaluate the visualised data to determine if there is a notable correlation

> The final step in the project involves analysing the visualised data for any correlations, which will in turn be used to draw a conclusion on whether the public sentiment towards Bitcoin has an impact on its value, and whether or not the popularity of the tweets has an influence on this correlation.




