# Twitter Sentiment Analysis - Airline Tweets

## 📌 Overview
This project performs sentiment analysis on airline-related tweets using Natural Language Processing (NLP) techniques. It involves data cleaning, feature extraction with TF-IDF, and training a Logistic Regression model to classify tweets into three sentiment categories :- POSITIVE, NEUTRAL, and NEGATIVE. The project includes visualizations to interpret the model's performance and identify the most influential words for each sentiment class.

---

## 📂 Dataset
- Source: [Kaggle - Twitter US Airline Sentiment](https://www.kaggle.com/datasets/crowdflower/twitter-airline-sentiment)
- Columns Used: text (tweet content), airline_sentiment (label)

---
## Installation

1. Clone the repository :-
```
git clone https://github.com/your-username/SAMYAK_Sentiment_Analysis.git
cd SAMYAK_Sentiment_Analysis
```

2. Create a virtual environment :-
```
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install the required dependencies :-
```
pip install -r requirements.txt
```

(Note: Create a requirements.txt file with the listed libraries or run pip freeze > requirements.txt after manual installation.)

---

## Features
- Loads and preprocesses a dataset of airline tweets.

- Cleans text data by removing URLs, mentions, hashtags, special characters, and stopwords.

- Encodes sentiment labels for machine learning.

- Trains a Logistic Regression model using TF-IDF vectorization.

- Visualizes the top 10 influential words for each sentiment category.

- Provides accuracy metrics and a confusion matrix for model evaluation.

---

## 🧠 Key Steps
1.-  Data Cleaning: Remove URLs, mentions, punctuation, emojis, stopwords, etc.

2.-  Feature Extraction: TF-IDF Vectorization

3.- Modeling: Logistic Regression for classification

4.- Evaluation: Accuracy, Confusion Matrix, Word Importance

5.- Visualization: Sentiment distribution, top predictive words per class


---

## 🔍 Insights
- Most tweets are Negative in sentiment.
- The model performs well with ~80% accuracy.
- Top keywords influencing each sentiment are printed and visualized.

---

## Screenshots

### Snap 1 :- 
<img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/56188b28-73eb-43b9-872e-a4c4f168a976" />

### Snap 2 :- 
<img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/a4e2f020-c381-49d1-9645-796b5ab6ab62" />


## 📄 Credits
- Dataset by Crowdflower (via Kaggle)
- NLP methods and modeling using Scikit-learn, NLTK, and CleanText
- Guided learning adapted from online tutorials

---

## Author 
**SAMYAK VAIDYA**  
Artificial Intelligence & Data Science Enthusiast  
Connect on [LinkedIn](https://www.linkedin.com/in/samyak-vaidya-4bb9b4282)

## ⚠️ Disclaimer
This project is for academic and learning purposes only. The dataset contains real tweets and should be used responsibly.

