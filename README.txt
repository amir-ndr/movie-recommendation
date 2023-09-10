
---

# Movie Recommendation System

This project implements a movie recommendation system using both Content-Based and Collaborative Filtering techniques in Python with the Pandas library.

## Content-Based Filtering

Content-Based filtering recommends movies to users based on the attributes or features of the movies they have previously rated. In this approach, the system explores users' preferences and recommends movies with similar content features.

## Collaborative Filtering

Collaborative Filtering recommends movies by finding patterns in user behavior and preferences. It identifies users with similar tastes and suggests movies liked by those similar users.

## About the Dataset

The dataset used in this project contains information about movies and user ratings. It includes movie titles, genres, and user ratings.

## Content-Based Filtering Steps

1. Preprocess the movie dataset.
2. Create a user profile based on their rated movies and genres.
3. Calculate similarity between movies based on content features.
4. Recommend movies similar to the user's preferences.

## Collaborative Filtering Steps

1. Collect user ratings and identify similar users.
2. Calculate the Pearson Correlation Coefficient to measure similarity.
3. Generate recommendations based on the preferences of similar users.

## Example Usage

The project includes example usage with user input, demonstrating both Content-Based and Collaborative Filtering recommendations for a set of movies and ratings.

## Recommendation Results

The project displays the top recommended movies based on both Content-Based and Collaborative Filtering methods.

---