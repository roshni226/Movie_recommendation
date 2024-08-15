# Movie Recommendation System

## Overview

This Python project provides a movie recommendation system. The system fetches movie data from The Movie Database (TMDb) and utilizes various features to recommend movies. The process involves several key steps:

1. **Download Movie IDs**: Retrieve a list of valid movie IDs from TMDb's daily exports.
2. **Fetch Movie Details**: Use TMDb's APIs to collect detailed information about movies, including plot, popularity, genre, average vote, number of votes, and more.
3. **Calculate Weighted Ratings**: Compute a weighted rating for each movie, considering the average rating, the number of votes, and the overall average rating.
4. **Generate Top 10 Movies**: Identify the top 10 movies based on their popularity.
5. **Movie Similarity**: Use NLP and cosine similarity to find movies similar to a given movie based on plot descriptions.
6. **Recommendation Function**: Define a function that takes a movie title as input and returns a list of the 10 most similar movies.

## Prerequisites

- Python 3.x
- Required Python libraries: `requests`,`response`,'json', 'csv', `pandas`, `numpy`, `scikit-learn`, `nltk`, `json`, etc.

## Setup Instructions

1. **Clone the Repository**

   ```bash
   git clone https://github.com/roshni226/Movie-recommendation.git
   cd movie-recommendation
