# Movie_Recommendation_System

🎬 Movie Recommendation System

A content-based movie recommendation system built using Python and machine learning techniques. This project suggests movies similar to a user’s (favorite movie) based on features like genres, keywords, cast, director, and tagline.

📌 Overview

This system analyzes movie metadata and recommends similar movies using:

TF-IDF Vectorization for text feature extraction
Cosine Similarity for measuring similarity between movies
Fuzzy Matching (difflib) to handle user input errors

🚀 Features
🔍 Search movies even with spelling mistakes
🎯 Personalized recommendations based on movie similarity
⚡ Fast similarity computation using vectorized operations
🧠 Uses NLP techniques for better recommendations

🛠️ Tech Stack
Python
Pandas – Data handling
NumPy – Numerical operations
Scikit-learn – ML utilities
TF-IDF Vectorizer – Text processing
Cosine Similarity – Recommendation logic
difflib – Fuzzy string matching

📂 Dataset
The project uses a movie dataset (movies_dataset.csv) containing:

Title
Genres
Keywords
Tagline
Cast
Director

⚙️ How It Works
Data Preprocessing
Select relevant features
Handle missing values
Feature Engineering
Combine text features into a single string
Vectorization
Convert text data into numerical vectors using TF-IDF
Similarity Calculation
Compute cosine similarity between all movies
User Input Handling
Match user input with closest movie title
Recommendation
Return top similar movies
