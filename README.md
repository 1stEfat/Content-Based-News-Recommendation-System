# News Recommendation System

A content-based recommendation system that suggests news articles based on user preferences using TF-IDF and cosine similarity.

## Features

- Content-based filtering using article text (title + abstract)
- Multiple recommendation methods:
  - Category-based recommendations
  - Keyword-based recommendations
- Interactive command-line interface
- Persistent storage of processed data

## Prerequisites

- Python 3.8+
- pip package manager

  
## Project Structure
Content-Based-News-Recommendation-System/
├── data/                   # Raw and processed data
│   ├── news.tsv            # Original dataset
│   └── processed/          # Processed data files
├── notebooks/              # Jupyter notebooks
│   ├── 01_data_preprocessing.ipynb
│   ├── 02_user_profile_construction.ipynb
│   ├── 03_content_similarity.ipynb
│   └── 04_ranking_and_recommendation.ipynb
├── results/                # Output files
│   ├── category_recommendations.csv
│   ├── keyword_recommendations.csv
│   ├── processed_news.pkl
│   ├── similarity_by_category.pkl
│   ├── similarity_by_keywords.pkl
|   ├── tfidf_features.pkl
│   ├── tfidf_vectorizer.pkl
│   └── user_profiles.pkl
├── requirements.txt        # Dependencies
└── README.md               # This file


**Note:** The `tfidf_features.pkl` file is not included in the repository due to its large size (typically several hundred MB). It will be automatically regenerated when running the preprocessing notebook.
