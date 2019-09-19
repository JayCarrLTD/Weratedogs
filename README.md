# Weratedogs Data Analysis Project

## Introduction
This project wrangles, analyzes, and creates visualization for the the tweet archive of Twitter user @dog_rates, also known as WeRateDogs. WeRateDogs is a Twitter account that rates user submitted pictures of people's dogs along with a humorous comment about the dog. This project was to developed in order to analyze the data that was obtained from the @dog_rates twitter account. The project utlized python for the pupose of exploring, cleaning, and creating visualizations. Each subsection of the analaysis is broken up into three seperate sections: Define, Code, and Test. 

# THE DATA
WeRateDogs downloaded their Twitter archive which contains basic tweet data (tweet ID, timestamp, text, etc.) for all 5000+ of their tweets as they stood on August 1, 2017

# INTRODUCTION

This program runs on Jupyter Notebook. Installation instructions can be found here: <a href ="https://jupyter.org/install.html">Link</a>
The following packages (libraries) need to be installed. You can install these packages via conda or pip. 

Tools used: Python, NumPy, Pandas, Matplotlib, Jupyter Notebook, Excel


# QUESTION

### Situation
An ad agency wants to perform a photoshoot for some of the cutest dogs on the internet. The agency is using the data obtained from the Weratedogs dataset to analyze and see which dog breeds are highest and most rated. They also want to feature the number one dog in their magazine.

# UNDERSTAND
The data that was obtained from the @dog_rates twitter account will be the main source of infromation. In order to answer the question, we will first need to clean the data before analaysis. 

Gather. I gathered data from three sources:

The Twitter archive #WeRateDogs, a csv file that contains the tweet, rating, dog name, and dog 'stage' in life (such as puppy).

An 'image prediction' file, or what breed of dog is in each tweet, according to a neural network.  I downloaded the image prediction file programmatically from Udacity's servers using the Requests library.

Twitter's API to gather retweet count and favorite count, two columns missing in the Twitter archive. I queried the API for each tweet's JSON data using Python's Tweepy library.

Assess. I assessed the data based on quality and tidiness. 

Low quality (‘dirty’) data has content issues such as missing, invalid, inaccurate, and inconsistent data. I assessed removing unnecessary columns, converting data types, making dog names title case, removing entries that were not really dogs, and removing outliers.

Untidy (‘messy’) data has structural issues. I assessed gathering dog stages from multiple columns into one, creating a ‘prediction’ column (Dog, Maybe Dog, Not Dog), and combining the three datasets into one.

Clean. I converted each assessment observations into action items. Each item was defined, coded, and tested to ensure the problem was fixed. I first addressed missing data, then structural issues, then quality issues. For example, there were lots of ‘rating’ outliers. Dogs were supposed to be rated from 1-10, but many were well above 10. I converted the ones I could to a ‘10’ scale, such as ‘165 out of 150’ became an 11 rating.

# EXPLORE
This project contains three main datasets that was used to complete this project.

<b>Tweet Archive</b> - The archive containing all the tweet data obtained from the @dog_rates twitter account.



<b>Additional Data Via Twitter API</b>

<b>Image Predictions File</b>
This file contains the image link for each dog used for the WeRateDogs run through a neural network that can claissify breeds of dogs. 
<ul>
  <li>tweet_id: The unique identififer for each tweet in the tweet table for we rate dogs dataset</li>
<li>in_reply_status_id: The unique identifer for the tweet reply</li>
<li>in_reply_to_user_id: The unique idenfier for the user who posted a reply</li>
<li>timestamp: The date and time the tweet was posted</li>
<li>source: The platform that the tweet was posted from</li>
<li>text: The text contained in the tweet</li>
<li>retweeted_status_id: The unique identifer for the retweeted post</li>
<li>retweeted_status_user_id: The unique user if for the retweeted post</li>
<li>retweeted_staus_timestamp: The time stamp of the retweet</li>
<li>expanded_urls: The photo URL</li>
<li>rating_numerator: The posted score for the dog</li>
<li>rating_denominator: The denominator for the highest value</li>
<li>jpg_url The url for the image</li>
<li>img_num The number the image is</li>
<li>name: The name of the dog</li>
<li>doggo: The type of dog</li>
<li>floofer: The type of dog</li>
<li>pupper: The type of dog</li>
<li>puppo: The type of dog</li>
<li>p1: The algorithm's #1 prediction for the image in the tweet</li>
<li>p1_conf: How confident the algorithm is in its #1 prediction</li>
<li>p1_dog: Whether or not the #1 prediction is a breed of dog</li>
<li>p2: The algorithm's second most likely prediction</li>
<li>p2_conf: How confident the algorithm is in its #2 prediction</li>
<li>p2_dog: Whether or not the #2 prediction is a breed of dog</li>
<li>p3: The algorithm's third most likely prediction</li>
<li>p3_conf: How confident the algorithm is in its #3 prediction</li>
<li>p3_dog: Whether or not the #3 prediction is a breed of dog</li>
<li>Unnamed: 0: Error column</li>
<li>favorites: Number of times the tweet was favorited</li>
<li>retweet_count: Number of times the tweet was retweeted</li>
  
 </ul>

# SOLVE
<a href="https://nbviewer.jupyter.org/github/JayCarrLTD/Weratedogs/blob/master/Weratedogs_analysis.ipynb">FULL PANDAS ANALYSIS</a>

# TRANSLATE
<a href="https://nbviewer.jupyter.org/github.com/JayCarrLTD/Weratedogs/blob/master/action_report.pdf">ACTION REPORT</a>
