# Emotion Classification with DistilBERT
A small NLP project that fine‑tunes DistilBERT to classify text into six emotions using the dair‑ai/emotion dataset.

What This Project Does
Loads and preprocesses the emotion dataset
Fine‑tunes DistilBERT for multi‑class classification
Evaluates the model with accuracy, weighted F1, and per‑class metrics
Plots a confusion matrix to show common mistakes

Dataset
dair‑ai/emotion
6 labels: sadness, joy, love, anger, fear, surprise
Train: 16k
Validation: 2k
Test: 2k

Model
Base model: distilbert‑base‑uncased
Tokenization with Hugging Face
Training with the Trainer API
Best model selected using weighted F1

Results
Accuracy: ~0.92
Weighted F1: ~0.92
Strong performance on most classes; surprise is the hardest to predict.

Tools Used
Python
PyTorch
Hugging Face Transformers
Datasets
Scikit‑learn

Matplotlib / Seaborn

📎 References
Dataset: dair‑ai/emotion

Model: distilbert‑base‑uncased

Hugging Face Transformers docs
