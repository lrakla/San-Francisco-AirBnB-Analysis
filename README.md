![](https://api.visitorbadge.io/api/VisitorHit?user=estruyf&repo=github-visitors-badge&countColor=%237B1E7A)

# San-Francisco-AirBnB-Analysis
Analysis of AirBnB listings of San Francisco for 2019-2020
# Motivation
This project allows a business analysis of AirBnB listings of San Franciso from http://insideairbnb.com/index.html. It asks and answers 3 questions :
1) What are the busiest months in San Francisco and the price variations of the same?
2) How does availbality and price differ with type of room?
3) How does availability and price vary with neighborhood?
My [blog post](https://medium.com/@rlulua/3-insights-into-airbnb-in-san-francisco-38913347cf4c) on medium summarises the insights for a non-techinical audience.

This is a part of Udacity Data Scientist Nanodegree course.
# Files
San Francisco Airbnb.ipynb - it contains the code and graphs for the analysis
1) calendar.csv - it is a zipped file containing the day wise availability 
2) reviews.csv - it is a summary version of reviews containing only the date, listing id and reviewer id.
3) listings.csv - it is a summary version of listings containing host id, listing id, neighborhood, availability etc.
# Libraries used
pandas,numpy,seaborn,calendar and matplotlib.pyplot
# Summary of results
1) The busiest months are August,September and October which is Fall season in the city characterized by warm, pleasant climates. Price is generally higher than average in those months with sharp dips from December to February which are generally very cold.
2) Shared rooms have the highest availability and lowest price. 
3) The neighborhoods have different availability and prices. The high listing neighborhoods seem to be in close proximity with each other. However, no proper correlation is seen between the price and availability.
# Acknowledgements
Some of the resources which were useful for the analysis and inspiration were:
1. Inside AirBnB which provided the labelled dataset
2. Josh Bernhard's [article](https://medium.com/@josh_2774/a-comparison-of-airbnb-homes-seattle-vs-boston-cdc0df2cfcd7) on medium 
3. Udacity Nanodegree for the project inspiration
# Future work
1. These findings can be used for a comparative analysis with other nearby cities like Los Angeles.
2. Sentiment analysis can be performed on the reviews
3. Further analysis of factors affecting price and ratings.
