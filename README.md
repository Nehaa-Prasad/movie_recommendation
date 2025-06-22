# 🎬 Movie Recommendation System

This is a machine learning-based movie recommendation system developed as part of a mini project. It suggests movies based on user preferences using content-based filtering techniques.

---

## 📌 Project Objective

Build a system that recommends movies similar to a user's selected movie using content features like genres, keywords, cast, and more.

---

## 🛠️ Tech Stack

- **Python**
- **Pandas, NumPy**
- **Scikit-learn (TF-IDF, Cosine Similarity)**
- **NLTK (optional for text cleaning)**
- **Jupyter Notebook**
- **Streamlit** (if deployed as a web app)

---

## 🚀 Features

- Content-based movie recommendations
- Clean and intuitive interface (if deployed)
- Fast similarity matching using cosine distance
- Easily extendable with collaborative filtering or hybrid models


---

## 🧪 How to Run Locally

### 1. Clone the repo
```bash
git clone https://github.com/Nehaa-Prasad/movie-recommendation.git
cd movie-recommendation 
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the notebook
Open Movie_recommendation_system.ipynb in Jupyter Notebook or VS Code and run the cells.

### 4. (Optional) Run Streamlit app
If you created a frontend:
```bash
streamlit run app.py
```
### ⚠️ Note:
The file `src/cosine_sim.pkl` was too large to be included due to GitHub's 100MB limit.

To run the project:
- Open the notebook `Movie_recommendation_system.ipynb`
- Run all the cells to regenerate the required `.pkl` files


---

## 🔮 Future Improvements
-Add collaborative filtering using user ratings
-Connect to a live movie API (e.g., TMDB)
-Deploy the model using Flask/Streamlit on Render/Heroku
