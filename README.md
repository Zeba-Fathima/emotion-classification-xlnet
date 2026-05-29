# 😃 Emotion Classification Using Fine-Tuned XLNet Transformer Model

## 📌 Overview

Emotion Classification Using Fine-Tuned XLNet Transformer Model is a Natural Language Processing (NLP) project that leverages the power of transformer-based deep learning models to automatically identify emotions from text.

The project utilizes **XLNet**, a state-of-the-art transformer architecture, fine-tuned on an emotion-labeled dataset to classify text into four emotional categories:

- 😊 Joy
- 😨 Fear
- 😠 Anger
- 😢 Sadness

The complete workflow covers data preprocessing, dataset balancing, label encoding, tokenization, model fine-tuning, evaluation, and real-world inference using the Hugging Face ecosystem.

---

## 🚀 Features

- Fine-tuned XLNet transformer for emotion classification
- Text preprocessing and cleaning pipeline
- Emoji and social media mention removal
- Dataset balancing for improved model performance
- Label encoding for multi-class classification
- Hugging Face Dataset integration
- XLNet tokenization and embedding generation
- Model training using Hugging Face Trainer API
- Model evaluation with accuracy metrics
- Model saving and loading for inference
- Real-time emotion prediction pipeline

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- CleanText
- Regular Expressions (Regex)
- PyTorch
- Hugging Face Transformers
- Hugging Face Datasets
- Hugging Face Evaluate
- Scikit-Learn
- XLNet (xlnet-base-cased)

---

## 🏗️ Project Architecture

```text
Dataset
   │
   ▼
Text Cleaning
   │
   ▼
Dataset Balancing
   │
   ▼
Label Encoding
   │
   ▼
Train/Test Split
   │
   ▼
XLNet Tokenizer
   │
   ▼
Tokenized Dataset
   │
   ▼
XLNet Fine-Tuning
   │
   ▼
Model Evaluation
   │
   ▼
Save Model
   │
   ▼
Emotion Prediction
```
