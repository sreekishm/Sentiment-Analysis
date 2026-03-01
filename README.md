# Sentiment-Analysis
This project performs web scraping and sentiment analysis on online text data. It extracts content using BeautifulSoup, applies NLP preprocessing with NLTK, generates Word2Vec embeddings, and builds a Random Forest classifier for sentiment prediction. Visual insights are provided through word clouds and data visualizations
# Overview
This project demonstrates an end-to-end Natural Language Processing (NLP) workflow:
- Web scraping text data from online sources
- Text preprocessing and cleaning
- Feature engineering using Word2Vec
- Sentiment classification using Machine Learning
- Data visualization using word clouds and plots
# Tech Stack
- **Python**
- **BeautifulSoup:** Web scraping
- **NLTK:** Text preprocessing & sentiment lexicon
- **Gensim (Word2Vec):** Word embeddings
- **Scikit-learn:** Random Forest classifier
- **Pandas & NumPy:** Data manipulation
- **Matplotlib:** Visualization
- **WordCloud:** Text visualization
# Project Workflow
## Web Scraping
- Extracts text data from web pages using BeautifulSoup
- Handles request headers and parsing
## Data Preprocessing
- Tokenization
- Stopword removal
- Stemming (Porter Stemmer)
- Text normalization
## Feature Engineering
- Word frequency analysis
- Word2Vec embeddings for semantic representation
## Sentiment Analysis
- Uses opinion lexicon from NLTK
- Trains a Random Forest Classifier
- Evaluates model using:
   - Accuracy Score
   - Classification Report
## Visualization
- Word frequency plots
- Word clouds for key terms
- Graphical representation of insights
  
