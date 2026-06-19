# Movie Recommendation System

## Description

This project implements a content-based movie recommendation system using Python and Scikit-Learn. The system recommends movies based on the user's preferred genre by calculating similarity between user input and movie descriptions.

## Features

* Accepts user preferred movie genre
* Uses TF-IDF Vectorization
* Uses Cosine Similarity for matching
* Recommends relevant movies
* Displays similarity scores

## Technologies Used

* Python
* Scikit-Learn
* TF-IDF Vectorizer
* Cosine Similarity

## How to Run

1. Open terminal or command prompt.
2. Navigate to the project folder.
3. Run:

python recommendation.py

## Working Principle

The user's preferred genre is converted into a TF-IDF vector. Movie descriptions are also converted into vectors. Cosine similarity is then used to measure similarity between the user preference and movie descriptions. Movies with the highest similarity scores are recommended.

## Author

Developed as part of the DecodeLabs AI Internship Program.
