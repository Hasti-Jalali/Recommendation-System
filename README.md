# User-User Collaborative Filtering Recommendation System

This repository contains code for building a recommendation system based on user-user collaborative filtering approach. The dataset used in this project consists of two files: game.csv and ratings.csv. The first file contains information about the games and the second file contains the ratings given by users, including the game id, user id, and the rating.

The objective of this project is to build a recommendation system that takes an user id as input and recommends 5 games with the highest similarity to the games that have not been rated by the user. The similarity between users is calculated using the Cosine Similarity metric.