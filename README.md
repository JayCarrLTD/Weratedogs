# Weratedogs
This project is wrangles (and analyzing and visualizing) the tweet archive of Twitter user @dog_rates, also known as WeRateDogs. WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. 

#OVERVIEW
Weratedogs is a Twitter proﬁle that rates the cuteness level of various dogs that are sent to them. The goal of this project was to analyze the data that was obtained to ultimately see which dog breeds are the cutest. The project has worked with three separate data ﬁles that contain various relevantdata. For analytical purposes, I used pythons pandas to explore, clean, and create visualizations for the data set. The ﬁrst steps with this project were storing the data ﬁles into appropriate datasets, including scrubbing the JSON ﬁle to make it manageable. After making copies of the ﬁles and storing them into their respective datasets, I was able to merge the data into a single CSV ﬁle for analysis. I then was able to visually and programmatically asses areas in the data that required corrections or updates. I noted these issues down underneath the exploratory phase of my project. After exploring and assessing the data, I then proceeded to clean and correct the issues that I found within the dataset. This including correcting data types, extracting values from data, removing retweets, etc. I broke down each problem into three sections: Deﬁne, which outlined the issue and how I was going to address it. Code, the code used to solve the problem, and Test, the code used to test the data to verify the code worked. Following the cleaning, I then proceeded to create programmatic visualizations for the data which included graphs about highest rated dog breed as well as which dog stages were the most popular. From this project, I was able to put my programming skills to the test. I was able to learn how to fully assess and clean dirty data and how to think about the problem ahead of time before leaping into trying to analyze the data.

# QUESTION
Which breed of dog is the highest and most rated dog on the weratedogs twitter profile?

# UNDERSTAND


# EXPLORE
This project contains three main datasets that was used to complete this project.

<b>Tweet Archive</b> - The archive containing all the tweet data for the 


<b>Additional Data Via Twitter API</b>

<b>Image Predictions File</b>
This file contains the image link for each dog used for the WeRateDogs run through a neural network that can claissify breeds of dogs. 
<ul>
  <li><b>tweet_id</b> - tweet identification number</li>
<li><b>jpg_url</b> - the url for the tweet image</li>
<li> <b>img_num</b> - the image number for the tweet</li>
<li> <b>p1</b> - predicted dog breed </li>
<li><b>p1_conf</b> - confidence of predicted dog</li>
<li> <b>p1_dog</b> - the actual dog breed</li>
<li><b>p2</b> - the second predicted dog breed</li>
<li><b>p2_conf</b> - confidence of the predicted dog</li>
<li><b>p2_dog</b> - the actual dog breed</li>
<li><b>p3</b> - the third dog breed prediction</li>
<li><b>p3_conf</b> - confidence of the third dog breed</li>
<li><b>p3_dog</b> - the actual dog breed</li> 
</ul>

# SOLVE
FULL PANDAS ANALYSIS

# TRANSLATE
SUMMARY SLIDE DECK
