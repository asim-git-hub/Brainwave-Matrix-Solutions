## 📊 Task 2: Social Media Sentiment Analysis  
This project is part of my Data Science/Data Analytics Internship – Task 2: Real-world Social Media Sentiment Analysis.

## 🔍 Project Objective  
The objective of this project is to analyze public sentiment from real Twitter data using Natural Language Processing (NLP). The dataset includes tweets related to airline services in the U.S., and the goal is to classify sentiments (positive, neutral, negative), visualize trends, and build a predictive sentiment model using Python.

## 📁 Dataset  
Source: [Twitter US Airline Sentiment – Kaggle](https://www.kaggle.com/datasets/crowdflower/twitter-airline-sentiment)  

This dataset contains tweets directed at major U.S. airlines, labeled by sentiment.  
Key features include:
- `text`: Tweet content  
- `airline`: Airline mentioned  
- `airline_sentiment`: Sentiment label (`positive`, `neutral`, `negative`)  
- `tweet_created`: Timestamp of the tweet  

## ⚙️ Tools & Libraries Used  
- Python 🐍  
- Pandas  
- NumPy  
- Matplotlib & Seaborn  
- NLTK (Natural Language Toolkit)  
- WordCloud  
- Scikit-learn  
- Google Colab  

## 📊 Key Analysis Performed  
- Data cleaning and text preprocessing (tokenization, stopword removal, lemmatization)  
- Sentiment distribution visualization  
- WordClouds for each sentiment class  
- TF-IDF vectorization of tweet text  
- Logistic Regression model to classify sentiment  
- Confusion matrix and classification report  
- Time-series plot of sentiment trends over time  
- Optional: Sentiment trends per airline  

## 🔍 Key Insights  
💬 Majority of tweets are negative, showing customer dissatisfaction trends.  
📅 Sentiment trends reveal peaks in negative tweets on specific dates (e.g., service disruptions).  
✈️ Airlines like United and American have a higher ratio of negative feedback.  
📈 The Logistic Regression model performs well in identifying sentiment with good precision and recall.
