# Text-Preprocessing-2
# Bag of Words (BoW) & TF-IDF Implementation for Text Classification 

This repository contains a Python script (`bowimplementation.py`) that demonstrates **text preprocessing, Bag of Words (BoW), n-grams, and TF-IDF vectorization** using **NLTK** and **scikit-learn**.

The script uses the **SMS Spam dataset** as a real-world example to show how raw text is converted into numerical features suitable for Machine Learning models.

---

## Features Implemented

### 1️ Dataset Loading
- Reads `spam.csv` dataset
- Handles non-UTF-8 encoding (`latin-1`)
- Renames columns for clarity:
  - `label` → spam/ham
  - `message` → SMS text

---

### 2️ Text Cleaning & Preprocessing
For each message:
- Removes non-alphabetic characters using regex
- Converts text to lowercase
- Tokenizes text
- Removes English stopwords
- Applies **WordNet Lemmatization**
- Reconstructs cleaned sentences into a corpus

---

### 3️ Bag of Words (BoW)
- Uses `CountVectorizer`
- Limits vocabulary size using `max_features`
- Supports:
  - Normal BoW
  - Binary BoW (`binary=True`)
- Converts text corpus into numerical vectors

---

### 4️ N-grams Implementation
Demonstrates different `ngram_range` values:
- Unigrams `(1,1)`
- Unigrams + Bigrams `(1,2)`
- Only Bigrams `(2,2)`
- Shows how vocabulary changes with different n-gram settings

---

### 5️ TF-IDF Vectorization
- Uses `TfidfVectorizer`
- Demonstrates:
  - Unigram TF-IDF
  - Bigram TF-IDF
- Explains feature importance via TF-IDF weights

---

##  Requirements

Install dependencies using:

```bash
pip install pandas numpy nltk scikit-learn
```
The script automatically downloads required NLTK resources:
wordnet
stopwords

## Author
Srijan Verma
Machine Learning & NLP Enthusiast
