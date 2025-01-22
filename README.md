# movie_recommed_system
This project is a movie recommendation system built with Streamlit and powered by a machine learning model. It recommends movies based on a selected title using cosine similarity and displays movie posters fetched from the TMDB API.
Overview
The movie recommendation system helps users discover movies similar to their favorites. By selecting a movie from the list, users receive a list of top 10 recommended movies along with their posters. This project leverages machine learning techniques to analyze the features of movies and find similarities between them. It uses the TMDB API to fetch and display movie posters, enhancing the user experience by providing visual context for the recommendations. The system is built with Streamlit, providing an interactive and user-friendly interface for users to explore movie recommendations easily.

Theory of Recommendation Systems
What is a Recommendation System?
A recommendation system is a subclass of information filtering systems that seek to predict the rating or preference a user would give to an item. They are widely used in various applications like movie recommendations, product recommendations, and content recommendations.

Types of Recommendation Systems
Content-Based Filtering: This method recommends items similar to those a user liked in the past. It relies on the attributes of the items and a profile of the user's preferences.

Collaborative Filtering: This method recommends items based on the preferences of similar users. It doesn't require the attributes of the items and instead focuses on user-item interactions.

Hybrid Methods: These methods combine content-based and collaborative filtering to provide more accurate recommendations.

The-recommendation-system-types

Cosine Similarity
In this project, we use cosine similarity to measure the similarity between movie titles. Cosine similarity is a metric used to measure how similar two vectors are. It is calculated as the cosine of the angle between two vectors projected in a multi-dimensional space. For movie recommendation, the vectors represent movie features, and the similarity score indicates how alike two movies are.

Installation
Clone the repository:

git clone https://github.com/your-username/movie-recommendation-system.git
cd movie-recommendation-system
Install the required packages:

pip install -r requirements.txt
Usage
Run the Streamlit app:

streamlit run app.py
Open your web browser and go to http://localhost:8501.

Select a movie from the dropdown list and click "Recommend" to get the top 10 recommended movies along with their posters.

Dataset
The dataset used for this project contains information about movies, including their titles and IDs. It is processed and stored in movie_data.pkl. The dataset is used to calculate the cosine similarity between movies.

Model
The model for recommending movies is based on cosine similarity. Cosine similarity is used to measure the similarity between movie titles. The model computes the similarity scores and suggests the top 10 similar movies based on the selected movie title.

Results
The system provides the top 10 recommended movies for any selected movie title. It also fetches and displays the posters of these recommended movies using the TMDB API.

