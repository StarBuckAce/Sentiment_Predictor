# Sentiment Classification using BERT for Mental Health Statements
This project implements a sentiment analysis model based on BERT (Bidirectional Encoder Representations from Transformers) to classify mental health-related statements into two categories: "Normal" or "Depressed." The model is fine-tuned on a custom dataset of mental health-related texts and trained using Hugging Face's Transformers library.

**Features:**
Prepares and tokenizes text data for BERT input.
Uses a custom dataset of mental health statements with sentiment labels.
Fine-tunes the BERT model for classification using Hugging Face's Trainer API.
Evaluates the model's performance on test data.
Makes predictions on new input text.
Requirements:
Python 3.x
Hugging Face transformers
torch
datasets

**How to Run:**
Clone the repository.
Install dependencies.
Prepare the dataset (customize or use the provided one).
Train the model using the provided training script.
Evaluate the model's accuracy and make predictions on new inputs.
