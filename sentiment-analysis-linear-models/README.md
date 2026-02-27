# Sentiment Analysis with Linear Models (TF-IDF + Logistic Regression)

This module implements an end-to-end text classification pipeline using classic linear models.

## What it does
- Text preprocessing (cleaning, lowercasing, lemmatization with POS tags)
- Feature extraction with TF-IDF (unigrams + bigrams)
- Baseline comparison (majority / dummy classifier)
- Logistic Regression training & evaluation
- Precision–Recall analysis (including macro averages)
- Learning curves
- Hyperparameter tuning (GridSearchCV / RandomizedSearchCV)
- 2D visualization of feature space with UMAP

## Dataset
The implementation uses the NLTK **subjectivity** dataset (objective vs subjective), a balanced binary classification setup.

## Folder structure
- `docs/` — report + assignment specification (reference)
- `src/` — implementation code (`.py`) and/or notebook demo (`.ipynb`)

## Notes
Academic origin (MSc NLP project), reorganized as a portfolio module.
