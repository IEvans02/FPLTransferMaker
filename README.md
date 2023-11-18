# FPLTransferRecommender
Attempt to make an FPL transfer recommender using the FPL API. The data includes xG, fixture and game by game related stats.

Recommender system will be created using matrix factorisation techniques used/discussed in my Matrix-Factorisation repository but in Python.

The data consists of the top 10 current players over the past 5 seasons and the data reflecting their user-team interactions, such as historical team selections, transfers, and the points earned by each player in a user's team for each gameweek.
There is also players breakdown data used, such as everyone individuals breakdowns of gameweek points.

Ideally, I would use a year where there was no disruption but due to the size of the data, I am taking the current season (2023/2024) data as it's the easiest to take.
A copy of the in progress data collection can be seen in the FPLTransferRecommender-Copy1.ipynb file where I use multiple api endpoints to generate a dataframe suitable for Matrix Factorisation. The needed data manipulation for one gameweek is provided.
