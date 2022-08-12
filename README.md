# Movie-Recommender

A little recommendation system that recommend movies to a user, using ml-latest-small [dataset](https://grouplens.org/datasets/movielens/) from MovieLens.
The Approach is, to find the Top 100 Neighbour User, based on same movies seen. Based on same movies seen, a similaritiy score between the user and each of the 100 top neighbour users is calculated. This similarity score is used together with the movie rating of each user, to calculate a movie score. The user gets the movies with the highest scores as recommendation.
