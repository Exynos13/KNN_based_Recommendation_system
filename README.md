# KNN based Movie Recommender system
## Description
Building a KNN based recommender system using collaborative filtering method which handles the data sparsity problem

## Data 
Movielens Dataset which consists:
-  100,000 ratings (1-5) from 943 users on 1682 movies.
-  Each user has rated at least 20 movies.
-  Simple demographic info for the users (age, gender, occupation, zip)

## Implementation
The model was able to handle the data disparity problem by making up data based on the user similarity while also introducing the item’s popularity weight into the computation of similarity. 
Whereas for new users the recommendataion by choosing the top most popular movie titiles by calculating the composite recommendation which is the product of the popularity of the movie and the mean rating. Thus presnting the user with the selection of top movies user might like. 
