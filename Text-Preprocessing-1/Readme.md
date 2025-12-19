# Text Preprocessing with NLTK 

This repository demonstrates **core Natural Language Processing (NLP) text preprocessing techniques** using the **NLTK (Natural Language Toolkit)** library.

The code is intended for **learning and experimentation**, especially for beginners in NLP and Machine Learning.

---

##  Features Covered

The script walks through the most important steps used in NLP pipelines:

### 1️ Tokenization
- Sentence tokenization
- Word tokenization
- Word-punctuation tokenization
- Treebank tokenizer

### 2️ Stemming
- Porter Stemmer
- Regexp Stemmer
- Snowball Stemmer

### 3️ Lemmatization
- WordNet Lemmatizer (verb-based lemmatization)

### 4️ Stopword Removal
- English stopwords removal
- Combined with:
  - Stemming
  - Lemmatization

### 5️ Part-of-Speech (POS) Tagging
- POS tagging using `averaged_perceptron_tagger`
- Stopword filtering before tagging

### 6️ Named Entity Recognition (NER)
- Entity chunking using `ne_chunk`
- Identifies:
  - Persons
  - Locations
  - Organizations
  - Dates, etc.

---

## Requirements

Install the required dependencies before running the script:

```bash
pip install nltk
```
The script downloads required NLTK resources automatically, including:
punkt
wordnet
stopwords
averaged_perceptron_tagger
maxent_ne_chunker
words

## Author
Srijan Verma
NLP & Machine Learning Enthusiast

