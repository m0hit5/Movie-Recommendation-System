# Movie Recommendation System

A content-based movie recommendation system built using Python, Flask, and the TMDB dataset. The system recommends movies based on a user's input by utilizing a bag-of-words approach for text vectorization and TF-IDFVectorizer for transforming movie descriptions into numerical vectors. Cosine similarity is used to find similar movies based on these vectors.

## Project Features

- **Content-Based Filtering**: Built the recommendation system using content-based filtering with a bag-of-words approach and TF-IDFVectorizer.
- **Cosine Similarity**: Implemented cosine similarity to calculate the similarity between movie vectors and identify similar movies.
- **Movie Recommendations**: Developed a function to recommend top N movies based on the user's input movie.
- **Web App**: Created a web application using Flask and Streamlit to get user input (movie name) and display recommended movies with their posters.
- **Deployed**: The system is deployed online and users can interact with the movie recommender.

## Recommender Systems Types

- **Content-Based Filtering**: Recommends items based on features of the items and a user's previous preferences.
- **Collaborative Filtering**: Recommends items by finding similar users and suggesting items that those users liked.
- **Hybrid Systems**: Combines both content-based and collaborative filtering methods.

## Steps to Build the Project

1. **Data Preprocessing**: 
    - Removed stop words, performed stemming/lemmatization, and handled missing data.
  
2. **Feature Extraction**:
    - Converted movie descriptions into vectors using TfidfVectorizer from scikit-learn.
  
3. **Cosine Similarity**:
    - Calculated the cosine similarity between movie vectors to find the most similar movies.

4. **Recommendation Function**:
    - Developed a Python function to recommend top N similar movies based on a given movie name.

5. **Web Application**:
    - Created a web app using Flask and Streamlit where the user can input a movie name and view the top 5 movie recommendations with their posters.

## Setup and Installation

### Prerequisites
Ensure you have the following libraries installed:
- Python 3.x
- `pickle`
- `streamlit`
- `requests`
- `Flask`
- `pandas`
- `scikit-learn`

You can install the required libraries using pip:
```bash
pip install streamlit requests Flask scikit-learn pandas
