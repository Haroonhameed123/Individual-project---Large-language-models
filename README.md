**IMDb Sentiment Analysis Using Fine-Tuned BERT**

This project applies sentiment analysis to the IMDb movie reviews dataset using a fine-tuned BERT model. The task is a binary classification problem where reviews are classified as positive or negative. A Logistic Regression model using TF-IDF features is also included as a baseline for comparison.

**Project Overview**

Loads the IMDb dataset from the Hugging Face Datasets library

Preprocesses text using the BERT tokenizer (bert-base-uncased)

Converts reviews into tokenized batches for model training

Fine-tunes a BERT model for sentiment classification

Trains a Logistic Regression baseline model using TF-IDF features

Evaluates models using accuracy, precision, recall, and F1-score

**Dataset**

50,000 movie reviews

25,000 training samples and 25,000 test samples

Balanced between positive and negative classes

**Training Details (BERT)**

Learning rate: 2e-5

Batch size: 16

Optimizer: AdamW

Weight decay: 0.01

Epochs: 5

**Results (Summary)**

Fine-tuned BERT achieves approximately 92% accuracy

Logistic Regression baseline achieves approximately 88% accuracy

BERT performs better across precision, recall, and F1-score

**Purpose**

This project was completed as part of an academic assignment to compare transformer-based sentiment analysis with a traditional machine learning baseline model.
