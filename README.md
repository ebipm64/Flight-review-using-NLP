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



b-2) Air_line count

![air_vs_count](https://user-images.githubusercontent.com/71351619/134270935-058cf5b9-d473-4214-a435-b63ce42012f9.png)

b-3) text length distribution based on the label

![text_length_vs_target](https://user-images.githubusercontent.com/71351619/134271034-56ac02fe-25ac-40f8-a175-b94b3452a3f9.png)

...............................................................................................................................................................

# Model Deployment

a)For text converting to vector use two method "Countvectorizer" and "TFIDF" 

b) Use the following algorithms and compare the results
1. LogisticRegression
2. SVC 
3. Linear SVC
4. Naive Base
5. RandomForest
6. GradientBoosting
...............................................................................................................................................................
# Models Evaluation
a) For evalauting the model use the following metrics:
1. Classificaion Report
2. Confusion_matrix
3. Plot_confusion_matrix

b) Comparing the models metrics it's seen the SVC algorithm worked the best

![ROC_SVC](https://user-images.githubusercontent.com/71351619/134781344-efddc1c2-1b95-4e81-8081-a69be32a6965.png)






<img width="495" alt="confusion matrixPNG" src="https://user-images.githubusercontent.com/71351619/134781393-8dba238c-54e3-4a46-8d9d-f11c5ce80f30.PNG">







<img width="364" alt="classification report" src="https://user-images.githubusercontent.com/71351619/134781416-79b39780-6a4d-4384-b4d4-c5ca9be6deeb.PNG">



 
