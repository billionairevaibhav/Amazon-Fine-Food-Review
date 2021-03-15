# Amazon-Fine-Food-Review

## Objective:

Given a text review, determine the sentiment of the review whether its positive or negative.

Data Source: https://www.kaggle.com/snap/amazon-fine-food-reviews
About Dataset

The Amazon Fine Food Reviews dataset consists of reviews of fine foods from Amazon.

Number of reviews: 568,454
Number of users: 256,059
Number of products: 74,258
Timespan: Oct 1999 - Oct 2012
Number of Attributes/Columns in data: 10

## Attribute Information:

 1.   Id
 2.   ProductId - unique identifier for the product
 3.   UserId - unqiue identifier for the user
 4.   ProfileName
 5.   HelpfulnessNumerator - number of users who found the review helpful
 6.   HelpfulnessDenominator - number of users who indicated whether they found the review helpful or not
 7.   Score - rating between 1 and 5
 8.   Time - timestamp for the review
 9.   Summary - brief summary of the review
 10.  Text - text of the review


## Decision Trees


 1.   Applied Decision Trees on Different Featurization of Data viz. BOW(uni-gram), tfidf, Avg-Word2Vec and tf-idf-Word2Vec
 2.   Used both Grid Search with random 30 points for getting the best max_depth
 3.   Evaluated the test data on various performance metrics like accuracy, f1-score, precision, recall,etc. also plotted Confusion matrix using seaborne
 4.   Plotted feature importance recieved from the decision tree classifier

## Conclusions:

1.  BOW Featurization(max_depth=8) gave the best results with accuracy of 85.8% and F1-score of 0.858.
2.  Decision Trees on BOW and tfidf would have taken forever if had taken all the dimensions as it had huge dimension and hence tried with max 8 as max_depth




