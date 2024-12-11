# Sentiment Analysis of User Reviews for Get Contact Application

## Overview
This repository contains a sentiment analysis project focused on user reviews of the Get Contact application. The analysis uses **BERT (Bidirectional Encoder Representations from Transformers)** to uncover insights into user opinions, identifying areas of satisfaction and dissatisfaction with the app’s features and services.

## Features
- **Preprocessing Pipeline:** Clean and tokenize user reviews for compatibility with BERT.
- **Model Training:** Fine-tuning IndoBERT Base P2 on labeled data.
- **Evaluation:** Confusion matrix, classification report, and sentiment distribution.
- **Visualization:** Word clouds and pie charts to showcase results.

## Project Workflow
This project follows the CRISP-DM framework:
1. **Business Understanding:** Identify actionable insights to improve app features and user experience.
2. **Data Understanding:** Utilize 1200 labeled and 2192 unlabeled reviews.
3. **Data Preparation:** Standardize and preprocess text for model input.
4. **Modeling:** Fine-tune IndoBERT with optimized hyperparameters.
5. **Evaluation:** Assess performance using metrics like accuracy and F1-score.
6. **Reporting:** Present findings using visualizations and actionable insights.

## Results
- **Accuracy:** 88.89% on test data.
- **Sentiment Distribution:**
  - Positive: 39.7% (1346 reviews).
  - Negative: 60.3% (2046 reviews).

## Visualizations
- **Word Clouds:** Highlight frequently used words in positive and negative reviews.
- **Pie Chart:** Illustrate sentiment distribution.

## Technologies
- **Programming Language:** Python
- **Libraries:**
  - Transformers (Hugging Face)
  - TensorFlow
  - Pandas/Numpy
  - Matplotlib/Seaborn
  - WordCloud
