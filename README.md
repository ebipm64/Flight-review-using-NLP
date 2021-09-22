# Flight-review-using-NLP
The Data Source: https://www.kaggle.com/crowdflower/twitter-airline-sentiment?select=Tweets.csv

This data originally came from Crowdflower's Data for Everyone library.

As the original source says,

A sentiment analysis job about the problems of each major U.S. airline. Twitter data was scraped from February of 2015 and contributors were asked to first classify positive, negative, and neutral tweets, followed by categorizing negative reasons (such as "late flight" or "rude service").

...............................................................................................................................................................
# Data Cleaning
The following were performed:

a) Check for null data

b) Remove unnecessary columns

c) Remvoe null data from data frame

d) Delete the "nue" label from data to simplify the model

...............................................................................................................................................................

# EDA(Explotory Data Analysis)
The following were done:

a) Pass text_clean function on "text" column to remove punctuation and clean the text

b) Do some EDA 

b-1) Boxplot

![air_sent_word_count](https://user-images.githubusercontent.com/71351619/134270824-5e199709-7739-42e4-b4a5-38288364a2ed.png)

b-2)![air_vs_count](https://user-images.githubusercontent.com/71351619/134270935-058cf5b9-d473-4214-a435-b63ce42012f9.png)
