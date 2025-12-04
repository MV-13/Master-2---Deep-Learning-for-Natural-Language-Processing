# Deep Learning for NLP – Labs 1 & 2  

This repository contains my work for the two labs of the *Deep Learning for Natural Language Processing* course.  
Both labs focus on building and analyzing neural language models, from simple baselines to more advanced architectures.

---

## 🔹 Lab 1 — Bag-of-Words & CNN for Text Classification

- Preprocessing of textual data (tokenization, vocabulary building, batching).
- Implementation of two models for sentence classification:
  - **Bag-of-Words MLP**  
  - **Convolutional Neural Network (CNN)** for text
- Training with cross-entropy loss and evaluation with accuracy.
- Comparison of model capacity, training dynamics, and generalization.

---

## 🔹 Lab 2 — Neural N-gram & LSTM Language Models


- Preprocessing for language modeling (special tokens, padding, mask).
- **Neural trigram model**:
  - Embeddings + feed-forward network over a 2-word context
- **Autoregressive LSTM**:
  - Variational dropout, word dropout  
  - Multi-layer recurrent architecture  
  - Temperature-based sentence generation  
- Random Search over hyperparameters and saving of best models.
- Evaluation with **perplexity** and qualitative analysis of generated sentences.

