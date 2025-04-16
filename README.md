# Monster Hunter Worlds Steam Review Sentiment Analysis using Natural Language Processing (2024-2025)

A natural language processing (NLP) project for sentiment analysis related to the Monster Hunter World (MHW) community and in-game experiences. This project employs techniques to analyze textual data, understand fan feedback, and derive sentiment patterns from reviews and discussions.

## Overview

The **MHW Sentiment NLP** project applies sentiment analysis techniques on text data sourced from the Monster Hunter World community. The goal is to:
- Classify fan reviews and discussions into positive, neutral, or negative sentiments.
- Provide insights that can help understand player satisfaction and identify areas for improvement.
- Experiment with various NLP models and preprocessing methods.

The repository includes all necessary code, scripts, and documentation to replicate the experiments or build upon the provided work.

## Features

- **Text Preprocessing:** Includes tokenization, stopword removal, stemming/lemmatization, vectorization, Features selection, and Word Embbeding.
- **Sentiment Classification:** Implements machine learning models to classify sentiment.
- **Machine Learning Models**:Random Forest & Logistic Regression
- **Performance Benchmark:** Various machine learning models implemented in this project and being compared for their performances.
  
## Dataset

The dataset consists of 10000 [Monster Hunter World Steam reviews](https://steamcommunity.com/app/570/reviews/) collected between 2024-2025 for more details, it can be seen in [mhw_raw.csv](https://github.com/menggiGit33/mhw-sentiment-nlp/blob/main/mhw_raw.csv). Cleaned data after going through data preprocessing can be accessed in [clean_data.csv](https://github.com/menggiGit33/mhw-sentiment-nlp/blob/main/clean_data.csv) 
## Installation

To set up the development environment locally, follow these steps:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/menggiGit33/mhw-sentiment-nlp.git
   cd mhw-sentiment-nlp
