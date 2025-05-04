# Hate Speech Detection System

A machine learning model to classify text as hate speech, offensive language, or neutral.

## Features
- Text preprocessing (cleaning, lemmatization)
- Logistic Regression classifier
- TF-IDF vectorization
- Model evaluation metrics
- Prediction API

## Technologies Used
| Technology | Purpose |
|------------|---------|
| Python | Main programming language |
| pandas | Data loading and manipulation |
| scikit-learn | Machine learning pipeline (Logistic Regression, TF-IDF) |
| NLTK | Text preprocessing (stopwords, lemmatization) |
| joblib | Model serialization |
| pathlib | Cross-platform path handling |

## Dataset
- Source: [Kaggle Hate Speech Dataset](https://www.kaggle.com/datasets/vkrahul/twitter-hate-speech)
- Columns: `tweet` (text), `class` (0=hate, 1=offensive, 2=neutral)
- Sample size: 25,000 tweets

## Installation
1. Clone repository:
   ```bash
   git clone https://github.com/yourusername/HateSpeechDetection.git


Install dependencies:
pip install -r requirements.txt

Download NLTK data: 
import nltk
nltk.download(['stopwords', 'wordnet'])

Usage :
Train the model:
python src/train.py

Make predictions:
python src/predict.py
(Interactive mode will launch)

Performance
Metric	Score
Accuracy	0.84
Precision	0.83
Recall	0.82
F1-score	0.83
