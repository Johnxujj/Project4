# Project4
# 1  Natural Language Processing with Disaster Tweets
Jiajie Xu, 11Mar2022

# 2 Overview

## Business Problem
Our local emergency department want to use social media to trace emergency occur. For example, when people post a tweet online, local police or 911 can read the news and come out for help immediately. However, there are too many text info online to sort by human, so we need to generate a sufficient machine learning approach. 
## Business proposal
Twitter has become an important communication channel in times of emergency.
The ubiquitousness of smartphones enables people to announce an emergency they’re observing in real-time. Because of this, more agencies are interested in programatically monitoring Twitter (i.e. disaster relief organizations and news agencies).
## Business solution
By using Natual language Processing model, we can recognize tweets and get real disaster from social media. In this way, we may able to help emergency ambulance locate and rescue on time. 

# 3 Data Loading and cleaning

## Import data https://www.kaggle.com/c/nlp-getting-started/overview
## data cleaning

# 4 EDA
## Disaster Tweets wordcloud 
## Positive tweets wordcloud
## Visualizing data distribution

# 5 LSTM MODEL
## Split dateset
## Generate model
## Train the model with cleaned data
## Visual accuracy and loss

# 6 Bert Model
## LOADING BERT MODEL
## Import data in model
## Fit the model
## Plot the loss and accuracy curves 

# 7 Conclusion
After analysis, my team believe this BERT is suitable for NLP on Twitter. And accuracy can be improved to 0.85 through iteration.​

We come into conclusion as below：​

Bert generate better accuracy results compared to LSTM with same iteration times, even though Bert cost more calculation time.​

By using our model, we successfully help tracing the emergency event by NLP. ​

In order to increasing accuracy, we can adding more balanced features like time, location, and etc.

# 8 Future work
1. With more time, I would like to dig into relationship between NLP models and make a  clear comparison.​

2. For other media content, we can try to fit the model and find results as well.​

3. I want to see if we can add image processing to capture the emergency.



Presentation PPT included in the repository.
Github link: https://github.com/Johnxujj/Project4.git

Files:

test.csv - the test set

train.csv - the training set

project4.ipynb NLP python program

README.md intro to this project

Folder:

Image - histogram generated for data visualization

data - original dataset package

File not upload:

glove.6B.100d too big to upload to github
