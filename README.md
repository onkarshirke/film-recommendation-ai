Thanks! Here's an updated and complete `README.md` file for your **AI Movie Recommendation System** built with **JavaScript (frontend)** and **Python (Flask backend)** using **Pandas**, **Scikit-learn**, and a **Kaggle dataset**:

---

````markdown
# 🎥 AI Movie Recommendation System

A full-stack AI-powered movie recommendation web application built using **Python (Flask)** for the backend and **JavaScript** for the frontend. The system suggests similar movies based on content using Natural Language Processing (NLP) techniques.

---

## 🌟 Features

- 🔍 Search for any movie and get AI-powered recommendations
- 🧠 Content-based filtering using TF-IDF and cosine similarity
- ⚙️ Flask backend API for processing and ML logic
- 🌐 Responsive and interactive frontend using HTML, CSS, and JavaScript
- 📊 Dataset from Kaggle: TMDB 5000 Movie Dataset

---

## 🧠 How It Works

1. **Data Preprocessing**: Using Pandas to clean and combine movie metadata (overview, genres, cast, crew).
2. **Feature Extraction**: Using Scikit-learn's TF-IDF vectorizer to convert metadata into numerical form.
3. **Similarity Matching**: Using cosine similarity to find the most similar movies.
4. **Flask API**: Exposes an endpoint to take movie input and return recommendations.
5. **Frontend (JavaScript)**: Sends AJAX requests to Flask API and dynamically displays recommended movies.

---

## 📁 Dataset Used

- 📦 Dataset: [TMDB 5000 Movie Dataset](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)
- Files:
  - `tmdb_5000_movies.csv`
  - `tmdb_5000_credits.csv`

---

## 🏗️ Tech Stack

| Layer     | Technologies Used                            |
|-----------|----------------------------------------------|
| Frontend  | HTML, CSS, JavaScript (vanilla)              |
| Backend   | Python, Flask                                |
| ML / Data | Pandas, Scikit-learn, Numpy                  |
| Dataset   | Kaggle (TMDB 5000 Movie Dataset)             |

---

## 🔧 Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/ai-movie-recommendation.git
cd ai-movie-recommendation
````

### 2. Install Python Dependencies

```bash
pip install -r requirements.txt
```

### 3. Add Dataset

Place the following files in the project root (download from Kaggle):

* `tmdb_5000_movies.csv`
* `tmdb_5000_credits.csv`

### 4. Run the Flask Server

```bash
python app.py
```

By default, the app runs at: [http://localhost:5000](http://localhost:5000)

---

## 🗂️ Project Structure

```
ai-movie-recommendation/
│
├── static/
│   └── script.js           # JavaScript frontend logic
│
├── templates/
│   └── index.html          # Frontend UI
│
├── app.py                  # Flask backend
├── recommender.py          # Movie recommendation logic
├── tmdb_5000_movies.csv    # Dataset
├── tmdb_5000_credits.csv   # Dataset
├── requirements.txt
└── README.md
```

---

## ⚙️ API Endpoint

* **`POST /recommend`**

  * Request: `{ "movie": "Inception" }`
  * Response: `{ "recommendations": ["Interstellar", "The Prestige", ...] }`

--
## 🧩 Future Improvements

* Add movie posters using TMDB API
* Add user-based collaborative filtering
* Deploy on Heroku / Render
* Enhance UI with frameworks like React or Vue

---

## 🧾 License

This project is licensed under the MIT License. See `LICENSE` for details.

---

## 🤝 Contributing

Contributions are welcome! Please fork the repo, make your changes, and submit a pull request.

---

## 📬 Contact

Made with ❤️ by Onkar Shirke
🔗 GitHub: [github.com/yourusername](https://github.com/onkarshirke)

