# 🎬 Movie Recommender System

A content-based movie recommendation system built using the TMDB dataset and cosine similarity. This project provides personalized movie suggestions based on user-selected titles, using natural language processing (NLP) and metadata such as genres, keywords, and overviews.

![Project Preview](assets/preview.png)

---

## 🚀 Features

- 🔍 Content-based filtering using bag of words + Cosine Similarity
- 📚 Trained on TMDB movie metadata
- 🧠 NLP techniques for vectorization and similarity scoring
- 🎨 Simple Streamlit UI (via `app.py`)
- 📓 Exploratory analysis notebook for dataset insights

---

## 📸 Preview

> *(Add a screenshot or a gif of your app here)*  
> Example:  
> ![Demo](assets/demo.gif)

---

## 🛠️ Tech Stack

| Tool | Usage |
|------|-------|
| 🐍 Python | Core programming |
| 🧪 Pandas, NumPy | Data analysis |
| 🎯 Scikit-learn | TF-IDF + Cosine similarity |
| 🌐 Streamlit | Web app frontend |
| 📊 Matplotlib / Seaborn | Visualizations (optional) |

---

## 🚀 How to Run Locally

```bash
# 1. Clone the repo
git clone https://github.com/Shrutijaiswar/movie-recommender-system.git
cd movie-recommender-system

# 2. Install dependencies
pip install -r requirements.txt

# 3. Run the app
streamlit run app.py
