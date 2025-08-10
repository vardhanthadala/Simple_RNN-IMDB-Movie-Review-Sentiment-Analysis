<h1>IMDB Movie Review Sentiment Analysis</h1>

A deep learning-powered web app to classify IMDB movie reviews as Positive or Negative using TensorFlow and Streamlit 🚀

<h3>📌 Overview</h3>
This project is a Sentiment Analysis Web Application built using TensorFlow for the machine learning model and Streamlit for the interactive interface.
It predicts whether a given movie review expresses positive or negative sentiment.

✨ Live Demo: [simplernn-imdb-movie-review-sentiment-analysis-bafgpsehxndqbnc.streamlit.app]
(http://simplernn-imdb-movie-review-sentiment-analysis-bhue2nvny9ktn35.streamlit.app/)


<h3>🚀 Features</h3>
✅ Real-time sentiment prediction for user input
✅ Upload .txt file for batch predictions
✅ Clean and responsive Streamlit UI
✅ Trained on 50,000 IMDB reviews
✅ Accurate Deep Learning Model with word embeddings

<h3>🛠 Tech Stack </h3>
Python 3.x
TensorFlow / Keras – Model training & inference
Streamlit – Web app
NumPy / Pandas – Data handling
Matplotlib / Seaborn – Visualization

<h3>📂 Project Structure</h3>

IMDB-Sentiment-Analysis/
│
├── app.py                 # Streamlit app
├── model/
│   ├── imdb_model.h5       # Trained model
│   ├── tokenizer.pkl       # Tokenizer
│
├── data/
│   ├── imdb_reviews.csv    # Dataset (optional)
│
├── requirements.txt        # Dependencies
└── README.md               # Documentation

<h3>📊 Dataset</h3>
We use the IMDB Movie Review Dataset from Keras Datasets, containing 50,000 labeled reviews:
✅ 25k Training (balanced positive/negative)
✅ 25k Testing
