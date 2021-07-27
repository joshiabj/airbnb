
1) INSTALLATIONS

Python Version- 2

The libraries installed/imported include:
-matplotlib
-seaborn
-re
-nltk
-WordCloud
-sklearn

2) PROJECT MOTIVATION
As part of the Airbnb inside initiative, this dataset describes the listing activity of home stays in Seattle, WA.

After a thorough assessment of the data, the main aim of this analysis was to determine the answers to the following three questions:
- What are the most expensive Neighborhoods to stay in Seattle and what drives the prices? 
- What are the key factors that influence price?
- Is there a relationship between review comments and prices?

3) FILE DESCRIPTIONS

There are three files in this dataset, but I decided to restrict my analysis to only two of the datasets namely:
listings.csv - includes full descriptions and average review score
reviews.csv - includes unique id for each reviewer and detailed comments.

4)HOW TO INTERACT WITH THE PROJECT

We looked at the most expensive neighborhoods to stay in Seattle. It could be gathered that in these neighborhoods people tend 
to list their entire homes more often. Also the number of amenities provided were more. Built a wordcloud for the amenities.

A deep dive into the key factors influencing price revealed that factors such as bedrooms, bathrooms and room type were the main factors that influenced price.
Correlation was used to see the key factors which an influence on price. Using these key factors, a linear regression model was built to predict the price.


Finally we observed that the review comments had no significant effect on the prices of the listed houses. 
The review comments were generally favorable indicating pleasant experiences for the people.
Carried out sentiment analysis and correlation analysis to see impact of reviews on prices.


5)Acknowledgements

This data source is a part of the airbnb inside source.
