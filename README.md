# 2022-Tweet-Sentiment-Analysis

To perform sentiment analysis on tweets from 2022, the following steps were taken:

The tweepy library was used to authenticate with the Twitter API and search for tweets containing a specified search query. The csv library was used to write the tweet data to a CSV file.

The pandas library was used to load the tweet data from the CSV file into a dataframe and preprocess the text data by removing stop words, punctuation, and special characters.

The TextBlob library was used to perform sentiment analysis on the tweet text and create a new column in the dataframe containing the sentiment results.

The seaborn library was used to create a bar plot of the adjective frequencies in the tweet text, and the matplotlib library was used to create a word cloud of the adjectives.

The matplotlib library was also used to create a histogram of the sentiment results to visualize the distribution of the sentiment scores.

In addition, the python-decouple library was used to mask the API keys when sharing the code on GitHub.
