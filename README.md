# Data Analysis

# Project 1: Exploring weather trends
Analyze local and global temperature data and compare temperature trends in the chosen location with general global temperature trends.

## Data
Extracting data from a given SQL Workspace and downloading the results to an excel file.


# Project 2: Investigate a Dataset (No Show Appointments)

## Data
This dataset collects information from 100k medical appointments in Brazil and is focused on the question of whether or not patients show up for their appointment. 
A number of characteristics about the patient are included in each row.


# Project 3: Analyze A/B Test Results
A/B testing is a method of comparing two versions of a webpage against each other to determine which one performs better. 

## Data:
Data file contain user id - timestamp - group: control, treatment - landing page: old page, new page - converte: 0,1


# Project 4: Wrangle and Analyze Data
Gather data from a variety of sources and in a variety of formats, assess its quality and tidiness, then clean it. 

## Data:
Enhanced Twitter Archive for @dog_rates, also known as WeRateDogs.
Twitter API (tweet_json.txt)
Image Predictions File
twitter archive master (combined and cleaned data)

### Extract data using Twitter API:

import tweepy
consumer_key = 'YOUR CONSUMER KEY'
consumer_secret = 'YOUR CONSUMER SECRET'
access_token = 'YOUR ACCESS TOKEN'
access_secret = 'YOUR ACCESS SECRET'
auth = tweepy.OAuthHandler(consumer_key, consumer_secret)
auth.set_access_token(access_token, access_secret)
api = tweepy.API(auth)


# Project 5: Communicate Data Findings
Data visualization techniques in the data analysis process and production of a short presentation.

## Data:
Loan Data from Prosper with Prosper Data Dictionary to Explain Dataset's Variables

### Create Slide Deck:
jupyter nbconvert Example_Project_Diamonds_Part2.ipynb --to slides --post serve --template output_toggle
