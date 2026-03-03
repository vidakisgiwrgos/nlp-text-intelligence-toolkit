# NLP Text Intelligence Toolkit

A structured portfolio of NLP model implementations, 
progressing from statistical methods to deep learning and transformer fine-tuning.

## 🚀 Quick Overview

| Module | Architecture | Task |
|--------|-------------|------|
| Language Modeling | N-grams | Text generation & correction |
| Linear Models | TF-IDF + Logistic | Sentiment Classification |
| Neural MLP | MLP | Text Classification & POS |
| RNN | BiGRU + Attention | Classification & Tagging |
| CNN | Stacked CNN + Residual | Classification & Tagging |
| Transformers | BERT | Fine-tuned Classification & POS |

## Modules

### 1) N-gram Language Modeling
Classic statistical language modeling with evaluation and practical text utilities.
- Folder: `language-modeling-ngrams/`

## Tech Stack
- Python
- NLTK
- Edit distance (Levenshtein)
- Evaluation metrics (WER / CER)

## Notes
Some modules originated from academic projects and are reorganized here as production-style portfolio work.

### 2) Sentiment Analysis with Linear Models
End-to-end text classification pipeline with TF-IDF n-grams and Logistic Regression, including strong evaluation (PR curves, macro averages, learning curves) and hyperparameter tuning.
- Folder: `sentiment-analysis-linear-models/`

### 3) Neural Text Modeling
Neural NLP projects focusing on MLP-based text classification and POS tagging with word embeddings.
- Folder: `neural-text-modeling/`

### 4) RNN Sequence Modeling
Recurrent neural network projects for text classification (BiRNN + self-attention) and POS tagging (BiRNN).
- Folder: `rnn-sequence-modeling/`

### 5) CNN Text Modeling
Stacked CNN projects for text classification and POS tagging (n-gram filters, residual connections, global max pooling).
- Folder: `cnn-text-modeling/`

### 6) Transformer Fine-Tuning
Fine-tuning BERT for subjectivity classification (sequence classification) and POS tagging (token classification).
- Folder: `transformer-finetuning/`

## Key Observations

- Linear TF-IDF models remain strong baselines for balanced binary classification.
- Deeper MLPs did not significantly outperform logistic regression.
- RNN stacking depth positively affected performance.
- CNN dimensionality scaling improved generalization.
- Transformer fine-tuning required more epochs and tuning to surpass classical methods.
