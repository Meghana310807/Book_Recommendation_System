# Book Recommendation System


# Overview

Recommendation systems help users discover relevant content by analyzing
historical interactions. This project leverages collaborative filtering
on user-book ratings to generate personalized book recommendations.

The system combines:

-   Item-based collaborative filtering
-   Cosine similarity
-   Popularity-based recommendations for new users
-   Flask web application for real-time recommendations

------------------------------------------------------------------------



# Dataset

**Dataset:** Book Recommendation Dataset

-   Source: Kaggle (Book-Crossing Dataset)
-   Processed over **1.15 million** user ratings
-   Includes:
    -   User information
    -   Book metadata
    -   User-book ratings

------------------------------------------------------------------------

# Project Structure

``` text
Book-Recommendation-System/
│
├── data/
│   ├── Books.csv
│   ├── Users.csv
│   └── Ratings.csv
├── notebooks/
│   └── recommendation_system.ipynb
├── models/
│   ├── similarity_matrix.pkl
│   └── popular_books.pkl
├── app.py
├── src/
│   ├── preprocessing.py
│   ├── recommender.py
│   ├── popularity_model.py
│   └── utils.py
├── templates/
├── static/
├── requirements.txt
├── README.md
└── LICENSE
```

------------------------------------------------------------------------

# Workflow

``` text
Book Ratings
      │
      ▼
Data Cleaning & Filtering
      │
      ▼
User-Book Rating Matrix
      │
      ▼
Cosine Similarity Computation
      │
      ▼
Item-Based Collaborative Filtering
      │
      ▼
Top-N Book Recommendations
```


------------------------------------------------------------------------
Github Link : 

