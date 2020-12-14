# Sentiment-Analysis-of-Tweets

This project will perform sentiment analysis on tweets using pyspark, starting from IDF score of each word to Logistic Regression. In Logistic Regression, we will compare the basic model with the model after tuning by ROC-AUC score and feature importance.

The tweets.csv file contains the following columns:
- <b>target:</b> the polarity of the tweet (0 = negative, 4 = positive)
- <b>ids:</b> The id of the tweet ( 2087)
- <b>date:</b> the date of the tweet (Sat May 16 23:58:44 UTC 2009)
- <b>flag:</b> The query (lyx). If there is no query, then this value is NO_QUERY.
- <b>user:</b> the user that tweeted (robotickilldozr)
- <b>text:</b> the text of the tweet (Lyx is cool)
