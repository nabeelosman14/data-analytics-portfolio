# 🧠 Sentiment Analysis of Elon Musk’s Twitter Takeover

## 📋 Overview
This project explores public sentiment around Elon Musk's acquisition of Twitter by analysing thousands of comments posted on Reddit and YouTube. The comments were extracted using public APIs, preprocessed using natural language techniques, and analysed using VADER for sentiment scoring and LDA for topic modelling.

## 📅 Project Summary
- Duration: 2 weeks
- Total Comments: Over 4,000
- Platforms Analysed: Reddit & YouTube
- Objective: Understand how public opinion varies by platform and sentiment

## 🧰 Tools Used
- Python (Pandas, NLTK, PRAW, YouTube API)
- VADER (Valence Aware Dictionary for Sentiment Reasoning)
- Gensim (LDA for topic modelling)
- WordCloud, Matplotlib (for visualisation)
- Jupyter Notebook
- Excel (cleaning raw exports)

## 🔍 Project Objectives
- Extract real-world social media comments using Reddit and YouTube APIs
- Preprocess and clean textual data: case normalisation, stop word removal, emoji stripping
- Apply VADER for sentiment scoring (positive, negative, neutral)
- Apply LDA to discover hidden discussion topics
- Visualise the results through word clouds and frequency histograms

## 📸 Sample Visuals

### 🔹 Word Cloud (Combined Dataset)
![Word Cloud](./Sentiment-Analysis-Elon-Musk-Twitter/images/word%20cloud.png)

### 🔹 Normalised Sentiment Score Distribution
![Sentiment Histogram](./Sentiment-Analysis-Elon-Musk-Twitter/images/Normalised%20sentiment%20score%20distribution.png)

## 📂 Files & Access

### 📁 Code
- 🧪 [Jupyter Notebook](./Sentiment-Analysis-Elon-Musk-Twitter/code/CombinedCommentInfo.ipynb)

### 📁 Data
- 📊 [Reddit Comments (Combined)](./Sentiment-Analysis-Elon-Musk-Twitter/data/1104-RedditCommentsCombined.xlsx)
- 📊 [YouTube Comments (Combined)](./Sentiment-Analysis-Elon-Musk-Twitter/data/3081-YouTubeCommentsCombined.xlsx)

### 📁 Report
- 📄 [Sentiment Analysis Report (PDF)](./Sentiment-Analysis-Elon-Musk-Twitter/report/Sentiment-Analysis-Elon-Musk-Twitter.pdf)

## 🧠 Skills Demonstrated
- Working with public APIs (Reddit & YouTube)
- Sentiment analysis using lexicon-based tools (VADER)
- Text preprocessing: emoji and link removal, tokenisation
- Topic modelling using Latent Dirichlet Allocation (LDA)
- Data storytelling using WordCloud and histograms

## 🔄 Challenges & Lessons Learned
- VADER doesn’t capture sarcasm or context well, making some sentiment classifications misleading
- Social media text is messy — requiring careful cleaning (e.g. emojis, links, language filtering)
- LDA’s topic interpretation required manual review to validate topic quality

## 🚀 Future Improvements
- Use transformer-based models like BERT or RoBERTa for deeper sentiment context
- Expand analysis to include tweets from the X (Twitter) API
- Segment sentiment analysis by age group or region (if metadata available)

---

> 📁 [Return to Main Portfolio](..)
