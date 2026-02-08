# Introduction to NLP — Practice Notebooks

This repository contains a collection of Jupyter notebooks created for **practicing and exploring Natural Language Processing (NLP)** concepts in Python.

The notebooks focus on hands-on experimentation with common NLP techniques, libraries, and workflows, including text preprocessing, tokenization, sentiment analysis, embeddings, and transformer-based models.

---

## Contents

- NLP fundamentals using Python
- Text preprocessing and normalization
- Tokenization and n-grams
- Sentiment analysis (rule-based and transformer-based)
- Word embeddings and vector representations
- Practical experiments using popular NLP libraries

---

## Environment & Dependencies

All notebooks were developed and tested inside a dedicated **conda environment** with the following package versions:

- python 3.11  
- nltk 3.9.1  
- pandas 2.2.3  
- matplotlib 3.10.0  
- spacy 3.8.3  
- textblob 0.18.0.post0  
- vaderSentiment 3.3.2  
- transformers 4.47.1  
- scikit-learn 1.6.0  
- gensim 4.3.3  
- seaborn 0.13.2  
- torch 2.5.1  
- ipywidgets 8.1.5  

---

## Setup Instructions (Recommended)

Using a virtual environment helps avoid dependency conflicts and keeps the project self-contained.

### Create and activate the environment
```bash
conda create --name nlp_env python=3.11
conda activate nlp_env