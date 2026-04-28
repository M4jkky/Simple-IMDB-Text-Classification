# Simple IMDB Text Classification

This folder contains an exploratory notebook that trains and evaluates simple text classification models on a subset of the IMDB movie reviews dataset.

## Notebook
- `imdb_text_classification.ipynb` — data loading, TF‑IDF vectorization, model training (SVC, Random Forest, Naive Bayes), and evaluation (accuracy, precision, recall, F1, confusion matrices).

## Key steps in the notebook
- Load dataset and inspect label distribution
- Subsample / balance classes for faster iteration
- TF‑IDF vectorization of review text
- Train SVC (linear), Random Forest, and Gaussian Naive Bayes
- Evaluate models with accuracy, precision, recall, F1, and confusion matrices

## Limitations
- The notebook uses a small subsample for speed; results are illustrative not production‑grade.
- GaussianNB requires dense inputs (the notebook converts the TF‑IDF matrix when training Naive Bayes), which can be memory‑heavy for large datasets.
