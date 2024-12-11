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

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/sentiment-analysis-getcontact.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Download the IndoBERT model weights.

## Usage
1. Prepare your dataset and place it in the `data/` directory.
2. Run the preprocessing script:
   ```bash
   python preprocess.py
   ```
3. Train the model:
   ```bash
   python train.py
   ```
4. Evaluate the model:
   ```bash
   python evaluate.py
   ```

## Future Improvements
- Add topic modeling for deeper insights.
- Include more diverse datasets for better generalization.
- Experiment with other transformer-based models.

## Contribution
Feel free to contribute by submitting issues or pull requests. Ensure code follows the repository’s style guide.

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

---

**Author:** [Dzaki Moch Fikri Aliffa]

**Contact:** [@dzakialiffa]
