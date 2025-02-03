# Book Recommendation System 📚

## Project Overview

A comprehensive Book Recommendation System built using Python, Flask, and machine learning techniques. The project provides two types of book recommendations:

1. Popularity-Based Recommendations
2. Collaborative Filtering Recommendations

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Flask
- HTML/CSS

## Features

- Display top-rated and most popular books
- Interactive book recommendation based on user's book selection
- Personalized book suggestions
- Responsive web interface

## Project Structure

```
book-recommendation-system/
│
├── app.py                 # Main Flask application
├── Books.csv              # Book details dataset
├── Users.csv              # User information dataset
├── Ratings.csv            # Book ratings dataset
│
├── templates/             # HTML templates
│   ├── index.html         # Home page
│   └── recommend.html     # Book recommendation page
│
├── popular.pkl            # Serialized popular books dataframe
├── pt.pkl                 # Serialized pivot table
├── books.pkl              # Serialized books dataframe
└── similarity_score.pkl   # Serialized similarity scores
```

## Recommendation Algorithms

### 1. Popularity-Based Recommendation
- Calculates book popularity based on:
  - Number of ratings
  - Average rating
- Displays top-rated books on the home page

### 2. Collaborative Filtering
- Uses cosine similarity to find books similar to a selected book
- Recommends books based on user rating patterns
- Provides personalized recommendations

## Data Preprocessing

- Handled missing values in datasets
- Merged and filtered datasets
- Created pivot table for collaborative filtering
- Calculated similarity scores between books

## How It Works

1. **Home Page**: 
   - Displays most popular books
   - Shows book title, author, image, number of ratings, and average rating

2. **Recommendation Page**:
   - User selects a book
   - System finds 5 most similar books based on collaborative filtering
   - Displays recommended books with details

## Future Improvements

- Implement user authentication
- Add more sophisticated recommendation algorithms
- Improve UI/UX
- Include more detailed book information

## Screenshots 

![Screenshot 2025-02-04 005910](https://github.com/user-attachments/assets/6f545ff0-b9c9-46a4-b652-095f0b0a1186)

![Screenshot 2025-02-04 010101](https://github.com/user-attachments/assets/8ce8f5b4-4efe-4884-b6c3-8c33d403d4f2)

