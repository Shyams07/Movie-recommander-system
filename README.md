![Screenshot 2023-09-28 200615](https://github.com/Shyams07/Movie-recommander-system/assets/96371609/5fab8145-96e8-4cfd-9239-3acbb98eb7a4)# Movie Recommender System

## Overview
This project implements a Movie Recommender System using machine learning techniques. It leverages a dataset of movie credits and movie lists from TMDb containing 5000 data points. The goal is to provide personalized movie recommendations to users based on their preferences and viewing history.

## Data Preprocessing
The project begins with data preprocessing, where we use Pandas and NumPy in Jupyter Notebook to clean and transform the raw data. This includes handling missing values, feature engineering, and preparing the data for model training.

## Model Development
Once the data is preprocessed, we proceed to build the recommendation model. This involves vectorizing the movie features and user preferences. This was achieved using the CountVectorizer from scikit-learn, which converts text data into numerical vectors.

## User Interface
To make the movie recommender system accessible to users, a user-friendly web interface has been developed. This interface allows users to input their preferences and receive movie recommendations in real-time. The web application has been built using Streamlit in PyCharm, providing an interactive and intuitive platform for users to discover new movies.

## Usage
1. Clone the repository to your local machine.
2. Install the required Python packages using `pip install -r requirements.txt`.
3. Launch the Streamlit web application by running `streamlit run app.py`.
4. Input your movie preferences, and the system will generate personalized recommendations.

## Dependencies
- Pandas
- NumPy
- Scikit-Learn (for machine learning models)
- Streamlit (for web interface)

## Dataset
The dataset used for this project can be obtained from TMDb or a similar movie database. It includes information about movie credits, cast, crew, genres, and more.

## Future Improvements
- Incorporate user feedback and ratings for better recommendation accuracy.
- Explore deep learning techniques for more advanced recommendation models.
- Enhance the web interface with additional features like user profiles and movie reviews.

  




