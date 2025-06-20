# 🎬 Movie Recommender System

An end-to-end machine learning project that recommends movies based on user preferences using collaborative and content-based filtering techniques.

## 🚀 Features

- 📊 Exploratory Data Analysis (EDA) on movie metadata
- 📚 Content-Based Filtering using TF-IDF on genres and descriptions
- 💾 Model training and serialization (Pickle)
- 🌐 Web app interface using Streamlit/Flask
- 🛠️ Ready for deployment
---

## 🧠 How It Works

This system uses this core approach:

**Content-Based Filtering**  
  Recommends movies similar to one the user liked based on genres, cast, director, and plot, among other factors.

---
## Project Structure:
movie-recommender-system/
│
├── notebooks/ # Jupyter notebooks for EDA and modeling
│ └── movie-recommender-system.ipynb
│
├── src/ # Python scripts for modular code
│ ├── data_loader.py
│ ├── recommender.py
│ └── utils.py
│
├── app/ # Streamlit or Flask app for UI
│ └── main.py
│
├── data/ # (Git-ignored) dataset storage
│
├── models/ # (Git-ignored) saved models
│
├── requirements.txt # Dependencies
├── .gitignore # Files to ignore
└── README.md # You're here!

## 📦 Installation

1. Clone the repository:

git clone https://github.com/yourusername/movie-recommender-system.git
cd movie-recommender-system

2. Install dependencies
pip install -r requirements.txt

3. Dataset 
Uses the TMDB 5000 movies dataset, available on kaggle: https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata

## Future Scope
1. Create login and signup functionality.
2. Add rating and feedback mechanism.
3. Personalized recommendations using collaborative filtering.
