# Disaster-Tweets

## What should I expect the data format to be?
Each sample in the train and test set has the following information:

1) The text of a tweet
2) A keyword from that tweet (although this may be blank!)
3) The location the tweet was sent from (may also be blank)


## What am I predicting?
You are predicting whether a given tweet is about a real disaster or not. If so, predict a 1. If not, predict a 0.

### Files
1) train.csv - the training set
2) test.csv - the test set

### Columns
1) id - a unique identifier for each tweet
2) text - the text of the tweet
3) location - the location the tweet was sent from (may be blank)
4) keyword - a particular keyword from the tweet (may be blank)
5) target - in train.csv only, this denotes whether a tweet is about a real disaster (1) or not (0)

## Approach
1) Importing the data
2) Data visualization
3) Data cleaning and Preprocessing 
4) Splitting the train data set into test and train split
5) Creating Model pipeline
6) Visualizing different Model Accuracy
7) Predicitng test data on the best model accuracy
