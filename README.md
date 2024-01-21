- Problem Definition

A sentiment analysis job about the problems of each major U.S. airline. Twitter data was scraped from February of 2015 and contributors were asked to first classify positive, negative, and neutral tweets, followed by categorizing negative reasons (such as "late flight" or "rude service").

- Data

The data was downloaded from kaggle[https://www.kaggle.com/datasets/crowdflower/twitter-airline-sentiment]

- Evaluation

The Evaluation metric is to get the best accuracy 

- Features

The data Features include tweet_id, airline_sentiment, airline_sentiment_confidence, negativereason, negativereason_confidence, airline,
airline_sentiment_gold, name, negativereason_gold, retweet_count, text, tweet_coord, tweet_created, tweet_location, user_timezone 

- Modelling

The Model used are Support vector machine(SVM) and Random Forest Classifier (RFC)
