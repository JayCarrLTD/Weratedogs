# Weratedogs Data Analysis Project

## Introduction
This project is wrangles, analyzes, and creates visulization for the the tweet archive of Twitter user @dog_rates, also known as WeRateDogs. WeRateDogs is a Twitter account that rates user submitted pictures of people's dogs along with a humorous comment about the dog. 


## Overview
This project was to developed in order to analyze the data that was obtained from the @dog_rates twitter account. The project utlized python for the pupose of exploring, cleaning, and creating visualizations. Each subsection of the analaysis is broken up into three seperate sections: Define, Code, and Test. 

# QUESTION
Which breed of dog is the highest and most rated dog on the weratedogs twitter profile?
Is it possible to determine the type of breed of a dog from a picture?

# UNDERSTAND
The data that was obtained from the @dog_rates twitter account will be the main source of infromation. The data will be used to ultimatley figure out which breeds are rated the highest. 

# EXPLORE
This project contains three main datasets that was used to complete this project.

<b>Tweet Archive</b> - The archive containing all the tweet data obtained from the @dog_rates twitter account.



<b>Additional Data Via Twitter API</b>

<b>Image Predictions File</b>
This file contains the image link for each dog used for the WeRateDogs run through a neural network that can claissify breeds of dogs. 

tweet_id: The unique identififer for each tweet in the tweet table for we rate dogs dataset
in_reply_status_id: The unique identifer for the tweet reply
in_reply_to_user_id: The unique idenfier for the user who posted a reply
timestamp: The date and time the tweet was posted
source: The platform that the tweet was posted from
text: The text contained in the tweet
retweeted_status_id: The unique identifer for the retweeted post
retweeted_status_user_id: The unique user if for the retweeted post
retweeted_staus_timestamp: The time stamp of the retweet
expanded_urls: The photo URL
rating_numerator: The posted score for the dog
rating_denominator: The denominator for the highest value
jpg_url The url for the image
img_num The number the image is
name: The name of the dog
doggo: The type of dog
floofer: The type of dog
pupper: The type of dog
puppo: The type of dog
p1: The algorithm's #1 prediction for the image in the tweet
p1_conf: How confident the algorithm is in its #1 prediction
p1_dog: Whether or not the #1 prediction is a breed of dog
p2: The algorithm's second most likely prediction
p2_conf: How confident the algorithm is in its #2 prediction
p2_dog: Whether or not the #2 prediction is a breed of dog
p3: The algorithm's third most likely prediction
p3_conf: How confident the algorithm is in its #3 prediction
p3_dog: Whether or not the #3 prediction is a breed of dog
Unnamed: 0: Error column
favorites: Number of times the tweet was favorited
retweet_count: Number of times the tweet was retweeted

# SOLVE
FULL PANDAS ANALYSIS

# TRANSLATE
SUMMARY SLIDE DECK
