# Analysis of Airbnb prices in Seattle
This code covers all of the analysis I performed in Python to generate the insights in my blog post "Making Sense of Airbnb Prices in Seattle": https://andrew-lee.medium.com/making-sense-of-airbnb-prices-in-seattle-87f4a2a1f51e 

# Installation
The analysis was done using Python 3.8.5

The following libraries were used: 
- scikit-learn
- pandas
- matplotlib

# Project Motivation and Summary
This code was written as part of Udacity's Data Science Nanodegree program.

Leveraging publicly available data from Airbnb with listing information from the Seattle market, we observed the following:
- Prices show significant variation by neighborhood
- Prices show moderate variation by time of year
- A linear model predicting price as a function of neighborhood, time of year, number of bedrooms, number of bathrooms, availability, and review score explains more than 50% of the variation in prices in the Seattle market.

Areas for future research include how to improve prediction accuracy, particularly for the small percentage of higher-end listings.

# File Descriptions
The file "Airbnb Analysis.ipynb" contains all of the code for this project

# Contact Me
Feedback and suggestions are always welcome: andrewsungjaelee@gmail.com

# Licensing, Authors, Acknowledgements
The analysis uses data obtained from Kaggle: https://www.kaggle.com/airbnb/seattle
