# FPLTransferMaker
Attempt to make an FPL transfer recommender using the FPL API. The data includes xG, fixture and game by game related stats.

Recommender system will be created using matrix factorisation techniques used/discussed in my Matrix-Factorisation repository but in Python.

All data is taken from the fantasy football API. The data consists of the top 10 2022/2023 finishers and the data reflecting their user-team interactions, such as historical team selections, transfers, and the points earned by each player in a user's team for each gameweek.
There is also players breakdown data used, such as everyone individuals breakdowns of gameweek points.

Ideally, I would use a year where there was no disruption, but for the matter of recency, I have gone for the 2022/2023 year.
