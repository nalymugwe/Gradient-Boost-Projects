# Gradient-Boost-Projects

## Problem Statement

The movie recommender platform is not trusted by customers so customers are leaving the movie recommender platform which is reducing the revenue.

The ideal solution would be to create an ideal recommnder system that gives accuurate suggestions that will retain customers.


## Data info

The data used was the Top 250 movies that was scraped from the imDb dataset.

The top 250 movies ranged from 1921 to 2021. It would be interesting to know which movie rocked the chart in 1921. Additionally it would be interesting to see which year had the most movies.

The ranking displays the top movie of all time, which was The Shawshank Redemption that had an imDB rating of 9.2 with a rating count of 2.5 million.

The year 1995 had the most movies in the Top250 chart with 8 movies, this was followed by 1957 that had 7 movies. It would be interesting to note these movies.


## Movie Analysis

An analysis of the top 10 directors and top 10 actors shows that they don't appear in the top 10 movies. Interestingly, the director that did Shawshank Redemption doesn't appear in the top 10 list. This shows that the director doesn't influence the rating of the movie. Same case applies for the actors. These features wouldn't be an influential feature in determining the rating of a movie.

It's quite obvious that the movies with the highest ratings received the highest count as seen in the bar graph.

The histogram displays a right skewed distribution showing a majority of the movies are ranked between a rating of 8 and 8.4


## Model Analysis

The algorithm that performs the best with a MAE score of 11, MSE of 192 and R2 of 0.94 is the Light GBM.

The most important feature is the number of ratings a movie receives.

The training model has an accuracy of 97% whereas the test model has an accuracy of 95%.
