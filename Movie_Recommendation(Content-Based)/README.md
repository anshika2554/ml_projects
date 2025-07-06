# 🎬 Movie Recommendation System

This project builds a **content-based movie recommender** using the TMDB 5000 Movie Dataset. It recommends movies based on genres, keywords, cast, crew, and overview — using Natural Language Processing (NLP) and cosine similarity.

---

## 🧠 What it Does

Given a movie title, the system returns a list of **similar movies** based on their content. It uses:
- Movie metadata (genres, cast, keywords, director, overview)
- Text vectorization with TFidVectorizer
- Cosine similarity for finding nearest matches

---

## 📁 Dataset Used

- [`tmdb_5000_movies.csv`](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)
- [`tmdb_5000_credits.csv`](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)

---

## 🛠️ How It Works

### 1. **Data Cleaning**
- Merged `movies` and `credits` datasets
- Removed nulls and unnecessary columns
- Parsed JSON-like fields (`genres`, `keywords`, `cast`, `crew`)

### 2. **Feature Engineering**
- Extracted top 3 cast members and director
- Combined genres, keywords, cast, crew, and overview into a single `tags` column
- Preprocessed text (lowercasing, removing spaces, etc.)

### 3. **Vectorization**
- Used `TFidVectorizer` 
- Converted `tags` into numerical vectors 

### 4. **Similarity**
- Used cosine similarity to compare movies
- Built a function `recommend(movie)` to get top 5 similar movies

---

## 🔍 Example Usage

```python
recommend('Inception')
```

## **💡 Future Improvements**
-	Add a Streamlit UI for user interaction
-	Include movie posters and metadata in output
-	Add popularity-based recommendations as a fallback
-	Deploy as a web app
---

## **📦 Requirements**
-	Python 3.x
-	pandas
-	scikit-learn
-	ast
-	numpy

```
CopyEdit
pip install pandas scikit-learn numpy
```
---

## **🧾 License**
This project is open-source and available under the [MIT License](LICENSE).
