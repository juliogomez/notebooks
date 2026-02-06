# ML & Transformer Notebooks

A collection of Jupyter notebooks for **training purposes**, designed to teach the fundamentals of transformer-based NLP models and practical machine learning workflows.

## Notebooks

### 1. The Transformer Model (CPU)

An introduction to how transformer models process text end-to-end. Covers tokenization, inference with pre-trained models, hidden states, attention mechanisms, and sentiment analysis using DistilBERT.

### 2. Fine Tuning VS Full Training (GPU)

A side-by-side comparison of two training approaches on the MRPC paraphrase detection task:

- **Fine-tuning** a pre-trained BERT model with the HuggingFace `Trainer` API.
- **Full training** with a custom PyTorch loop including manual backpropagation, optimizer steps, and learning rate scheduling.

### 3. Building a Classifier Model from Scratch (GPU)

Builds a text classifier on the 20 Newsgroups dataset (18,000 posts across 20 topics) using Google Gemini API embeddings fed into a simple Keras neural network.

## Disclaimer

This repository is intended **solely for educational and training purposes**. The notebooks, code, and examples provided here are meant to help learners understand machine learning concepts and should not be used as-is in production environments.
