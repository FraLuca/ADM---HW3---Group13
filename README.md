# ADM---HW3---Group13
This is the homework 3 for Data Science ADM

## Find the perfect place to stay in Texas!

In this homework we analyze the text of Airbnb property listings and building a search engine. In particular we build three increasingly performing search engines:

1) The first give back all the announcements that contain the key words queried

2) The second give back the top k announcements more similar with the query. k is decided by the user

3) The third do the same thing of the previous but use another idea of "similar", decided by us

********

### Dataset used

For this purpose we use the data in the [Kaggle site](https://www.kaggle.com/PromptCloudHQ/airbnb-property-data-from-texas). 
Dataset contains more than 18,000 property listings from Texas, United Staes. Given below are the data fields:
Rate per night, Number of bedrooms, City, Joining month and year, Longitude, Latitude, Property description, Property title, Property URL.

********

## Script Description

> __`Homework 3 - Group 13.ipynb`__ 

This script is divided in this way:
- First we download the data, then we clean it by stopword, punctuation and those that seemed us wrong. At the end we store each review in a single tsv file.
- Then we do all the search engines requested.
- At the end there's a bonus part with the map.

A detailed description is provided in the file. 

********

## Visualization Problem

If you can't see some plot or map please try to see at this link: 
