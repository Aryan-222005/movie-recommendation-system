# 🎬 Movie Recommendation System

An intelligent **content-based movie recommendation system** that recommends movies based on their similarity to a selected movie.

The system uses **TF-IDF Vectorization and Cosine Similarity** to analyze movie metadata and generate relevant recommendations. It also integrates the **TMDB API** to provide movie posters, ratings, genres, release dates, popularity, and other movie information.

The project combines **Machine Learning, FastAPI, Streamlit, and API integration** into a complete web application.

---

## 🚀 Live Demo

🎬 **[Launch CinemaMatch AI](https://cinemamatch-ai.streamlit.app/)**

⚡ **[Backend API](https://movie-recommendation-system-dono.onrender.com/)**

📚 **[API Documentation](https://movie-recommendation-system-dono.onrender.com/docs)**

---

## 🚀 Features

- 🎬 Content-based movie recommendations
- 🔍 Movie search using TMDB API
- 🤖 TF-IDF based similarity
- 📐 Cosine similarity for recommendation ranking
- 🎭 Genre-based recommendations
- ⭐ Movie ratings and metadata
- 🖼️ Movie posters and movie details
- 🔥 Trending and popular movies
- ⚡ FastAPI backend
- 💻 Streamlit frontend
- ☁️ Cloud deployment

---

## 🧠 How It Works

The recommendation system follows this pipeline:

```text
Movie Dataset
      ↓
Data Preprocessing
      ↓
Feature Engineering
      ↓
Text Preprocessing
      ↓
TF-IDF Vectorization
      ↓
Cosine Similarity
      ↓
Similarity Ranking
      ↓
Movie Recommendations
```
---

## 📊 Recommendation Approach

## TF-IDF

TF-IDF (Term Frequency-Inverse Document Frequency) converts movie metadata into numerical vectors based on the importance of words.

---

## Cosine Similarity

Cosine similarity calculates the similarity between movie vectors. Movies with higher similarity scores are recommended to the user.

---

## 🌐 TMDB API Integration

The TMDB API is used to retrieve movie information such as:

Movie posters
Ratings
Genres
Release dates
Popularity
Movie descriptions
Movie details

---

## 🛠️ Tech Stack

Machine Learning
Python
Pandas
NumPy
Scikit-learn
TF-IDF
Cosine Similarity

---

## Backend

FastAPI
Uvicorn
HTTPX

---

## Frontend

Streamlit
API
TMDB API
Deployment
Render
Streamlit Community Cloud

---

## 📂 Project Structure

```
movie-recommendation-system
│
├── Dataset
│   └── movies_metadata.csv
│
├── Images
│   ├── homepage.png
│   ├── movie_search.png
│   ├── recommendations.png
│   └── recommendations2.png
│
├── app.py
├── main.py
├── movies.ipynb
│
├── df.pkl
├── indices.pkl
├── tfidf.pkl
├── tfidf_matrix.pkl
│
├── requirements.txt
├── .python-version
├── .gitignore
└── README.md
```

---

 ## 💻 Run Locally

## 1️⃣ Clone the repository

```bash
git clone https://github.com/Aryan-222005/movie-recommendation-system.git
```

## 2️⃣ Navigate to the project

```bash
cd movie-recommendation-system
```

## 3️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

## 4️⃣ Add TMDB API Key

## Create a .env file:

```bash
TMDB_API_KEY=your_tmdb_api_key
```

⚠️ Never commit your .env file or API key to GitHub.

## 5️⃣ Run FastAPI

```bash
uvicorn main:app --reload
```

## Backend:

```bash
http://127.0.0.1:8000
```

## API Documentation:

```bash
http://127.0.0.1:8000/docs
```

## 6️⃣ Run Streamlit

Open another terminal:

```bash
streamlit run app.py
```

## Frontend:

```bash
http://127.0.0.1:8501
```

## 📸 App Preview


## 🏠 Home Page

![CinemaMatch AI Homepage](images/homepage.png)

---


## 🔍 Movie Search

![CinemaMatch AI Movie Search](images/movie_search.png)

---

## 🎬 Recommendations

![CinemaMatch AI Recommendations](images/recommendations.png)
![CinemaMatch AI Recommendations](images/recommendations2.png)


---

## ☁️ Deployment

The application uses a two-part architecture:


```
             GitHub
                │
       ┌────────┴────────┐
       ↓                 ↓
    Render         Streamlit Cloud
       │                 │
    FastAPI  ◄───────────┘
       │
   ┌───┴────┐
   ↓        ↓
 ML Model  TMDB API
 ```

Backend: Render
Frontend: Streamlit Community Cloud

---

## 🔮 Future Improvements

Hybrid recommendation system
Collaborative filtering
User authentication
Personalized recommendations
Favorites and watchlists
User preference learning
Movie trailers
Database integration

---

## 👨‍💻 Author

Aryan Singh

B.Tech CSE (Honours) — AI/ML

GitHub:

https://github.com/Aryan-222005


⭐ If you like this project, consider giving it a star!
