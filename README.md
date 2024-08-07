# Topic-Modeling-Analysis-on-Twitter

## Overview
This project aims to analyze tweets from selected Twitter accounts, focusing on political figures from California and Florida. By filtering, cleaning, and applying various natural language processing techniques, we aim to identify and visualize key topics discussed by these politicians.

## Data Collection

### Twitter Data
- Collected tweets using Tweepy from a list of California and Florida politicians.
- Data collection was performed within a specific date range.
- Tweets were filtered based on their relevance to the study.

### Data Source
- Extracted the list of politicians' names and Twitter accounts from a website using BeautifulSoup.
- Compiled the scraped data into an Excel file named `Data Science Twitter list.xlsx`.

## Data Preprocessing

### Cleaning
The tweets underwent a comprehensive cleaning process:
- Removal of mentions, retweets, hyperlinks, and punctuation.
- Conversion to lowercase.
- Removal of numbers, emojis, and other non-alphabetic characters.
- Removal of special patterns, including certain Unicode characters and non-English text.

### Tokenization
- Cleaned text was tokenized into individual words.

### Stopwords Removal
- Removed common English stopwords to focus on meaningful content.

### Lemmatization
- Words were lemmatized to their base forms for consistency in text analysis.

### Keyword Filtering
- Filtered tweets using a list of keywords related to environmental issues, climate change, and policy.
- Retained only tweets containing these keywords for further analysis.

## Natural Language Processing

### Topic Modeling
- Used Latent Dirichlet Allocation (LDA) for topic modeling to identify key topics discussed in the tweets.

### Sentiment Analysis
- Performed sentiment analysis to gauge the overall sentiment of the tweets, categorizing them into positive, negative, or neutral sentiments.

### Visualization
- Created various visualizations, such as word clouds and topic distribution plots, to illustrate the analysis results.

## Dependencies
- Tweepy
- BeautifulSoup4
- Pandas
- Numpy
- NLTK
- Scikit-learn
- Matplotlib
- Seaborn

## Learning Curves
Working on this project involved several learning curves:
- **Web Scraping with BeautifulSoup:** Extracting data from websites and handling HTML structures.
- **Twitter API with Tweepy:** Authenticating and collecting data from Twitter.
- **Text Preprocessing:** Cleaning and preparing text data for analysis.
- **Natural Language Processing:** Implementing techniques such as tokenization, lemmatization, stop words removal, and topic modeling.
- **Data Visualization:** Creating insightful visualizations to present the findings effectively.
