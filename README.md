
# Fake News Classifier

## Overview
This project implements a machine learning-based fake news classifier using natural language processing (NLP) techniques. It analyzes news articles to distinguish between fake and factual content through multiple analysis methods including sentiment analysis, topic modeling, and classification algorithms.

## Features

### 1. **Text Analysis**
- **POS Tagging**: Part-of-speech tagging using spaCy to identify word types
- **Named Entity Recognition (NER)**: Extracts and analyzes named entities (organizations, persons, locations, etc.)
- **Text Preprocessing**: Cleaning, tokenization, lemmatization, and stopword removal

### 2. **Sentiment Analysis**
- VADER sentiment analysis to classify articles as negative, neutral, or positive
- Distribution analysis comparing sentiment across fake and factual news

### 3. **Topic Modeling**
- **LDA (Latent Dirichlet Allocation)**: Discovers topics in fake news articles
- **LSI (Latent Semantic Indexing)**: Alternative topic modeling approach using TF-IDF
- Coherence score evaluation to determine optimal topic numbers

### 4. **Classification Models**
- **Logistic Regression**: Primary classification model
- **SGD Classifier**: Support Vector Machine-based alternative
- Performance metrics including accuracy and classification reports

## Dataset
- File: `fake_news_data.csv`
- Columns: `text`, `fake_or_factual`

## Dependencies
- pandas, matplotlib, seaborn
- spaCy, NLTK
- scikit-learn
- Gensim
- VADER Sentiment

## Key Results
Models evaluate classification performance using accuracy scores and detailed classification reports with precision, recall, and F1-scores.
