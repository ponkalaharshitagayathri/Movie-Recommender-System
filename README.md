Movie Recommendation System

This project implements a content-based movie recommendation system using Python and scikit-learn. It leverages the TMDB 5000 Movies and Credits datasets to recommend movies based on similarity in content such as genres, cast, crew, keywords, and plot overview.

How It Works

Preprocesses and cleans movie metadata from TMDB datasets.

Extracts meaningful features including genres, keywords, top cast, director, and movie overviews.

Combines all features into a unified tags representation.

Uses CountVectorizer to convert text data into numerical vectors.

Applies cosine similarity to compute similarity between movies.

Recommends the top 5 most similar movies based on user input.

Technologies Used

Python

Pandas, NumPy

scikit-learn

NLTK (Porter Stemmer)

Jupyter Notebook

TMDB Dataset

Key Features

Content-based personalization using movie metadata.

Efficient similarity computation using vectorized text features.

Simple and extensible recommendation function.

Can be easily integrated with a web interface (Flask / Streamlit).

🚀 How to Run

Clone the repository

Install dependencies

pip install numpy pandas scikit-learn nltk


Ensure movies.csv and credits.csv are present in the project directory.

Open and run movie_recommendation_system.ipynb in Jupyter Notebook.

 Example
recommend("Avatar")
recommend("Iron Man")
