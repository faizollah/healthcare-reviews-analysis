# Healthcare Reviews Analysis
This repository contains an analysis of healthcare reviews to extract sentiments, keywords, and other insights. The code processes, visualizes, and analyzes reviews sourced from a Kaggle dataset.

## Overview
- Data Import and Cleaning: Loaded a CSV dataset of healthcare reviews and handled missing values.
- Initial Data Exploration: Obtained basic statistics and visualized the distribution of reviews among different healthcare companies.
- Sentiment Analysis:
  - Used TextBlob for a basic sentiment analysis.
  - Employed VADER sentiment analysis.
  - Integrated BERT-based sentiment analysis using the transformers library.
  - Combined the results from the three methods for an ensemble sentiment analysis.
- Sentence-based Sentiment Analysis: Tokenized the reviews into individual sentences and performed sentiment analysis on each sentence.
- Keyword Extraction: Utilized TF-IDF to extract the most relevant phrases from the reviews.
- Adjective Pairings: Detected adjective-noun pairings from positive reviews using spaCy.
- Topic Modeling: Implemented LDA (Latent Dirichlet Allocation) to categorize the reviews into different topics.
- Named Entity Recognition (NER): Used spaCy to extract and categorize named entities from reviews.

## Dataset
The dataset used in this analysis was sourced from Kaggle. You can find it [here](https://www.kaggle.com/datasets/joealvarez/healthcare-reviews). It provides a set of reviews related to various healthcare companies.

## Dependencies
- Primary Libraries: pandas, matplotlib
- NLP Libraries: TextBlob, VADER, spaCy, transformers, nltk, gensim
- Others: tqdm, torch, sklearn

## Report
For a comprehensive overview of the findings and insights derived from this analysis, please refer to the attached report. It provides detailed interpretations of the visualizations, sentiment scores, keyword extractions, and topic models.
