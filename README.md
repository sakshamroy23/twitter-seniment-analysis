# 🐦 Twitter Sentiment Analysis (Live Data)

This project performs **real-time sentiment analysis** on tweets fetched using the Twitter API. It classifies tweets into categories such as **positive**, **neutral**, or **negative** sentiments using natural language processing techniques.

---

## 📌 Project Overview

- **Goal:** Analyze live Twitter data to determine public sentiment on various topics.
- **Data Source:** Live tweets fetched using the **Twitter API**
- **Output:** Visualized sentiment distribution & classified tweet content

---

## 🚀 Features

- 🔁 Live Twitter data extraction using `tweepy`
- ✂️ Text preprocessing (cleaning, tokenization, stopword removal)
- 🧠 Sentiment classification using NLP models
- 📊 Visualizations with Matplotlib/Seaborn
- ✅ Results interpretation: polarity scores, label counts

---

## 🔧 Tech Stack

- **Python 3.x**
- **Tweepy** – Twitter API integration
- **TextBlob / VADER** – Sentiment analysis
- **Pandas / NumPy** – Data handling
- **Matplotlib / Seaborn** – Visualization
- **Jupyter Notebook** – Interactive analysis

---

## 🧠 Workflow

1. **Twitter API Setup**  
   - Authenticate with Twitter using `tweepy`
   - Define search query and fetch tweets

2. **Text Preprocessing**  
   - Remove links, mentions, hashtags, punctuations
   - Normalize text (lowercase, stopword removal)

3. **Sentiment Analysis**  
   - Use models like `TextBlob` or `VADER` to determine:
     - Polarity (positive/neutral/negative)
     - Subjectivity

4. **Visualization**  
   - Pie charts / bar plots of sentiment distribution
   - Word clouds of most common words

---


