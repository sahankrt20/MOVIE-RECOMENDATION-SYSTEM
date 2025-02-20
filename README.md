# Movie Recommendation System

## Overview
This project is a simple movie recommendation system using collaborative filtering. It leverages user ratings to find and suggest movies similar to the ones users have watched and rated highly.

## Features
- Uses **collaborative filtering** based on movie ratings.
- Computes **cosine similarity** between movies.
- Provides **movie recommendations** based on user input.
- Works with datasets like `movies.csv` and `ratings.csv`.

## Dataset
The system requires the following datasets:
1. **movies.csv**: Contains movie information with columns:
   - `movieId`: Unique identifier for each movie.
   - `title`: The name of the movie.

2. **ratings.csv**: Contains user ratings with columns:
   - `userId`: Unique identifier for each user.
   - `movieId`: Movie identifier (linked to `movies.csv`).
   - `rating`: User rating for a movie.

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/sahankrt20/MOVIE-RECOMENDATION-SYSTEM
   cd MOVIE-RECOMENDATION-SYSTEM

