# BERT Subjectivity Classifier (Fine-Tuning)

Fine-tuned a small BERT model for binary text classification (subjective vs objective).

## What’s included
- Dataset preparation with stratified splits (train/validation/test)
- Tokenization via `AutoTokenizer`
- Fine-tuning with Hugging Face `Trainer`
- Metrics: accuracy + macro F1
- Optional freezing of the base encoder (parameter-efficient tuning style)

## Files
- `docs/` – specification + report (reference)
- `src/` – implementation (.py)
- `notebooks/` – notebook demo (.ipynb)

## Collaboration
Team submission (3 members). Co-authors listed in the report.
