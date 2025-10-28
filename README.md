# NLP-Sentiment-and-Grammar-Parser
A simple NLP project that combines sentiment analysis using Naive Bayes with syntactic parsing based on NLTK Context-Free Grammar (CFG).


This project demonstrates two fundamental NLP techniques:
1. **Sentiment Analysis** – Classifies short movie reviews as positive or negative using a Naive Bayes classifier.
2. **Grammar Parsing** – Uses NLTK's Context-Free Grammar (CFG) to analyze the syntactic structure of movie-related sentences.

The goal is to provide a simple yet insightful introduction to text classification and linguistic parsing using Python.

---

## Features
- Preprocesses a small dataset of movie reviews.
- Converts text into numerical form using `CountVectorizer`.
- Trains a **Multinomial Naive Bayes** model for sentiment prediction.
- Builds a **CFG (Context-Free Grammar)** for parsing sentence structures.
- Visualizes the parse tree using NLTK.

---

## Technologies Used
- **Python**
- **Pandas**
- **Scikit-learn**
- **NLTK**

---
Example Output 
F-1 Score: 1.0000

Parsing sentence:
          S
    ______|______
   NP             VP
 _|__          ___|___
Det   N       V       NP
 |    |       |     ___|____
the director loved  Det      N
                    |        |
                    the     plot
                            |
                           with
                             |
                           NP
                           / \
                         Det  N
                          |   |
                          a  character

