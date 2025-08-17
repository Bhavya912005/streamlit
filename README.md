A content-based recommendation system that suggests movies and TV series similar to the one you like. Just pick a movie or series from the carousel and get top 5 closest recommendations instantly!

https://app-app-hmppergkvr2huuruxdcrj5.streamlit.app/

✨ Features

✅ Personalized recommendations using content similarity
✅ Cosine similarity and vector closeness for accurate results
✅ Pre-trained model stored as Pickle file for fast response
✅ Interactive Streamlit UI with an easy-to-use carousel
✅ Lightweight, deployable, and open-source

🛠 Tech Stack

Python (core logic)

Pandas, NumPy (data handling)

Scikit-learn (cosine similarity & vectorization)

Pickle (model serialization)

Streamlit (frontend UI)

Project Structure
├── app.py                # Streamlit app entry point
├── model.pkl             # Pickle file for pre-computed similarity data
├── movies.csv            # Dataset of movies and series
├── requirements.txt      # Python dependencies
├── README.md             # Project documentation

How It Works

Dataset processing: Movies/series metadata (title, genre, etc.) converted into feature vectors.

Similarity calculation: Cosine similarity finds the closest matches to the selected title.

Recommendation: Top 5 similar titles are returned.

Streamlit UI: Interactive carousel to select a movie/series and see recommendations instantly.
