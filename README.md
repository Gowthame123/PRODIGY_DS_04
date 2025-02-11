# PRODIGY_DS_04

# 📊 Sentiment Analysis of Tweets using TextBlob

## 🔍 Project Overview
This project performs sentiment analysis on tweets using TextBlob to determine their sentiment polarity and classify them as Positive, Negative, or Neutral. The dataset used contains tweets labeled with topics and sentiments.

## 📂 Dataset
Source: Twitter dataset (assumed from PRODIGY Internship).
Columns:
ID: Unique identifier for each tweet.
Topic: Subject of the tweet.
Sentiment: Pre-labeled sentiment of the tweet.
Tweet: The text content of the tweet.
Preprocessing Steps:
Removed null values from the Tweet column.
Computed sentiment polarity using TextBlob.
Classified tweets as Positive, Negative, or Neutral.

## 🛠 Tech Stack
Programming Language: Python 🐍
Libraries Used:
pandas - Data manipulation
textblob - Sentiment analysis
matplotlib & seaborn - Data visualization

## 🚀 Implementation Steps
### 1️⃣ Load & Preprocess the Dataset
Read the Twitter dataset (twitter_training.csv).
Drop rows with missing tweets.
### 2️⃣ Perform Sentiment Analysis
Compute Polarity Score (TextBlob) for each tweet.
Classify tweets as Positive, Negative, or Neutral based on polarity.
### 3️⃣ Visualize the Sentiment Distribution
Count the number of tweets per sentiment category.
Plot a histogram to visualize sentiment polarity distribution.

## 📊 Results & Observations
The dataset was successfully analyzed for sentiment polarity.
Most tweets fell into Positive, Negative, or Neutral categories.
A histogram plot was generated to visualize the polarity distribution.

## 🏆 Future Enhancements
Implement VADER for better sentiment scoring.
Compare performance with ML models (e.g., Logistic Regression, SVM).
Deploy as a Streamlit web app for real-time sentiment analysis.
