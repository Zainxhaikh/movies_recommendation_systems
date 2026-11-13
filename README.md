# Movie Recommender System

A Content-Based Movie Recommender System that suggests similar movies based on the movie you select.

Live Demo: https://moviesrecommendationsystems-nnecfnpsrsog6mbzbb2mfx.streamlit.app/

## Tech Stack
- Python
- Pandas, NumPy, Scikit-learn
- Streamlit
- TMDB API for movie posters

## How it Works
- Uses Content-Based Filtering with Cosine Similarity
- Movie dataset with genres, overview, cast, crew combined into tags
- Tags converted into vectors using CountVectorizer
- Similarity matrix calculates how similar each movie is to others
- When user selects a movie, system recommends top 5 similar movies with posters

## Project Files
- `app.py` - Streamlit web app
- `movies_recommendation.ipynb` - Model training notebook
- `movies.pkl` - Movies dataframe
- `similarity.pkl` - Similarity matrix

## How to Run Locally
1. Clone this repo
2. Install requirements: `pip install -r requirements.txt`
3. Run: `streamlit run app.py`
4. Select any movie and get top 5 recommendations

## Features
- Select any movie from 5000+ movies
- Get 5 similar movie recommendations instantly
- Movie posters fetched live via TMDB API
- Clean Streamlit UI

## Author
Zain Ul Abidin - Aspiring AI/ML Developer
Live Demo: https://moviesrecommendationsystems-nnecfnpsrsgg6mbzbb2mfx.streamlit.app
This is the project for Movies recommendations.
