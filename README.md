## Movie Recommender System

This is a project I did in one of my classes in school.

### Introduction
Are you tired of spending more time on the next movie to watch after seeing a movie? Since you are in a good mood and would like to continue and watch a movie based on the genre of the last watched movie, this recommender system would alleviate you from decision fatigue. Your watching history, genre interests, and even your mood are considered by the recommendation algorithm to suggest movies that are specially tailored for you. 

### Dataset
The datasets used in this recommendation algorithm are three: movies, genres, and ratings. 

### Description
For this project, before we could start conducting recommender systems, I needed to filter the movies based on it being a comedy. The movie used in building this recommender system is Antz - an animated comedy movie produced by DreamWorks.

To create the recommender system, I had to first run PCA to identify the number of components to include when creating correlation matrix. The dimensions were reduced to a more reasonable number that still captures the explained variance.

Additionally, I also created a movie recommender system using SVD, since the SVD does a better job than the PCA when the data is sparse like in this instance.

This would help end-users to explore their personalized movie recommendations. Pick a movie, grab some popcorn, and enjoy your movie night.

