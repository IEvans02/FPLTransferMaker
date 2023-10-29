# FPLTransferRecommender
Attempt to make an FPL transfer recommender using the FPL API. The data includes xG, fixture and game by game related stats.

Recommender system will be created using matrix factorisation techniques used/discussed in my Matrix-Factorisation repository but in Python.

The data consists of the top 10 2022/2023 finishers and the data reflecting their user-team interactions, such as historical team selections, transfers, and the points earned by each player in a user's team for each gameweek.
There is also players breakdown data used, such as everyone individuals breakdowns of gameweek points.

Ideally, I would use a year where there was no disruption (World Cup, Covid), but for the matter of recency, I have gone for the 2022/2023 year.
A copy of the in progress data collection can be seen in the FPLTransferRecommender-Copy1.ipynb file where I use multiple api endpoints to generate a dataframe suitable for Matrix Factorisation. The needed data manipulation for one gameweek is provided.
