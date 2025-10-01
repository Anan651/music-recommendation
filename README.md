# 🎵 Music Recommendation System

This project is a **content-based music recommendation system** that suggests similar songs based on their lyrics. It uses **Natural Language Processing (NLP)** techniques such as text cleaning, tokenization, stopword removal, and **TF-IDF vectorization** to find lyrical similarity between songs using **cosine similarity**.

---

## 📂 Project Structure

```

music-recommendation/
│
├── src/
│   ├── main.py                  # Entry point to run the recommendation system
│   ├── preprocess.py            # Functions for text preprocessing (cleaning, TF-IDF)
│   ├── recommend.py             # Functions for recommending songs
│   └── spotify_millsongdata.csv # Dataset containing songs and lyrics
│
├── app.ipynb                # Jupyter Notebook for exploration and testing
├── requirements.txt         # List of dependencies
└── README.md                # Project documentation

````

---

## ⚙️ Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Anan651/music-recommendation.git
   cd music-recommendation
2. **(Optional) Create a virtual environment**

   ```bash
   python -m venv venv
   venv\Scripts\activate      # On Windows
   source venv/bin/activate   # On Mac/Linux
3. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

---

## ▶️ Usage

Run the project from the command line:

```bash
python src/main.py
```

Or import and use in Python:

```python
from src.recommend import recommend_song

print(recommend_song("Hello"))
# Returns top 5 recommended songs similar to "Hello"
```

---

## 📊 Dataset

The project uses the **Spotify Million Song Dataset**, which contains:

* `song` → Song title
* `text` → Lyrics of the song

You can download it from [Kaggle](https://www.kaggle.com/datasets/adarshphadnis/spotify-million-song-dataset).

---

## 🛠️ Built With

* **Python 3.9+**
* **Pandas** – Data manipulation
* **NLTK** – Tokenization & stopword removal
* **Scikit-learn** – TF-IDF & cosine similarity
* **Jupyter Notebook** – For experiments

---

## 🚀 Future Improvements

* Add a web app interface (Flask/Streamlit)
* Use artist and genre information in recommendations
* Improve scalability for large datasets

---

## 👨‍💻 Author

**Anan Ahmed**

* GitHub: [Anan651](https://github.com/Anan651)

```
