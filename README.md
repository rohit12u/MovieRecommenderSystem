# MovieRecommenderSystem
🎬 Movie Recommendation System
A simple content-based movie recommender system built with Python using pandas, scikit-learn, and cosine similarity. This project lets users upload a dataset and get movie recommendations based on genre similarity.

📌 Features
📤 Upload your own movie dataset (CSV or Excel format)

🎯 Get top-N movie recommendations based on genre similarity

🧠 Uses CountVectorizer and Cosine Similarity

📊 View and preview uploaded dataset

💻 Built with Streamlit (web app) and also available as a Jupyter Notebook

🗃 Dataset Format
Your dataset should contain at least these columns:

Column	Description
movieId	Unique identifier for each movie
title	Title of the movie (with year)
genres	Genres separated by `

🛠 Tech Stack
Python

pandas

scikit-learn

Streamlit (for UI)

Jupyter Notebook (for script version)

🚀 How It Works
Upload your movie dataset.

Genres are vectorized using CountVectorizer.

Similarity scores are calculated using cosine_similarity.

Based on a selected movie, top-N similar movies are recommended.
