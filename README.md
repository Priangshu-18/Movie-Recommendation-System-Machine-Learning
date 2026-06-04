# Movie Recommendation System

Content-based movie recommendation engine using TF-IDF and cosine similarity on the TMDB dataset.

## Overview

- Feature engineering from genres, keywords, cast, crew, and overview text
- TF-IDF vectorization of combined features
- Cosine similarity matrix for nearest-neighbour lookup
- Returns top 5 similar movies for any given title

## Tech Stack

Python, Scikit-learn, Pandas, NumPy

## Run

```bash
pip install scikit-learn pandas numpy jupyter
jupyter notebook movie_recommendation.ipynb
```
