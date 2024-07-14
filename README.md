# Interactive Movie-Recommendation-System

## Overview
The Movie Recommendation Engine project aims to develop a recommendation system for "MyNextMovie," a startup focused on providing personalized movie suggestions across various OTT platforms. This project utilizes collaborative filtering, content-based filtering, and popularity-based approaches to recommend movies based on user preferences and movie characteristics.

## Business Understanding
"MyNextMovie" seeks to enhance user engagement by offering tailored movie recommendations. By analysing user ratings and movie metadata from the MovieLens dataset, the project aims to predict user preferences accurately, thereby improving user satisfaction and retention.

## Data Understanding
The project utilizes two main datasets from MovieLens:
It avaible from (https://www.kaggle.com/code/ayushimishra2809/movie-recommendation-system/data?select=ratings.csv)
* Movies Dataset: Contains details such as movie titles, genres, and IDs.
* Ratings Dataset: Includes user ratings for different movies, along with timestamps.
The analysis covers 105,339 ratings for 10,339 movies across various genres, providing a rich dataset for building recommendation models.
There are two data files which are provided:
Movies.csv
* movieId: ID assigned to a movie
* title: Title of a movie
* genres: pipe separated list of movie genres.

Ratings.csv
* userId: ID assigned to a user
* movieId: ID assigned to a movie
* rating: rating by a user to a movie
* Timestamp: time at which the rating was provided

## Methodology
1. Popularity-Based Recommendations
 
Implemented a popularity-based recommender that suggests popular movies within specific genres based on user-defined thresholds for minimum ratings.

3. Content-Based Recommendations
   
Utilized TF-IDF vectorization to analyze movie genres and recommend similar movies based on genre similarity.

5. Collaborative Filtering Recommendations
   
Implemented collaborative filtering to recommend movies based on similar users' preferences. This method identifies users with similar movie-watching behaviors and recommends movies they enjoyed but the target user hasn't seen yet. 

## Results
The recommendation engine successfully recommends movies based on different methodologies:

* Popularity-Based: Recommends top-rated movies in specified genres.
* Content-Based: Suggests movies with similar genres to a given movie.
* Collaborative Filtering: Recommends movies based on similar users' preferences.
