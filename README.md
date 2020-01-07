# Seattle-Airbnb-Analysis
## Table of Contents
1. Librarie Used
2. Project Motivation
3. File Description
4. Summary of results
5. Acknowledgements


## Libraries Used
1. Numpy
2. Pandas
3. Matplotlib
4. Sklearn

## Project Motivation
This project was part of Udacity Data Science project. This project will help me understand the how to use everday data for prediction, sentiment analsyis. Some of the data analysis done for this project are:
1.Investigate the index affecting the prices
2.Sentiment analysis of the reviews
3.Investigate the popular times of the year for the Seattle Airbnb

## File Description
 The jupyter notebook shows the analysis done on the seattle based Airbnb rentals data set. Data preparatoin, data cleaning and prediction is done on the listing data set. Sentiment analysis is done on the review dataset and finally a closer look on the popular times of the year is done using the calendar data set.
 If we look into the seattle folder, it contains the data set from https://www.kaggle.com/airbnb/seattle. 
* calendar.csv contains availability of listings and price
* listing.csv contains information on listings
* review.csv contains reviews by user

## Summary of the Results
1. The feature that affects the pricing are number of bedrooms, number of accomadation, avialiblity of private rooms and neighborhood.
2. Sentiment analysis
 * Negative Sentiment 
 
"Day" is the most negative correlated word. This must have came up as the room was availabe for one day.
"Kevin" a person name is also a negative word. This seems to be like a host name and this name must have came up in the comments many times which had lower review_score.
"both" is not something that can be associated with sentiment analysis.
* Positive Sentiment 

"Days" as compared to "Day" means that have a range of days of availiblity had a high impact for higher score.
"great" is often associated with a great service or great host
"clean" was something that was expected, as a clean room recieves a positve score.
"location" also means that the neighbourhood was good or the location was ideal.
3. January is the most popular times of the year for seattle airbnb.

## Acknowledgements
Credit to Airbnb dataset: https://www.kaggle.com/airbnb/seattle
Python Machine Learning by Sebastian Raschka and Vahid Mirjalili
Sentiment analysis: https://towardsdatascience.com/uber-reviews-text-analysis-11613675046d

