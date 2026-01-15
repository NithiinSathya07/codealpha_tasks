# Chatbot for FAQs

## Task Overview

This project is developed as part of **Internship Task 2: Chatbot for FAQs** under an AI-based internship program.

The objective of this task is to build a simple chatbot application capable of answering frequently asked questions (FAQs) related to a specific topic or product. The chatbot processes user input using Natural Language Processing (NLP) techniques and returns the most relevant answer from a predefined dataset.

This project uses **Python** along with **NLTK, NumPy, TensorFlow, and scikit-learn** libraries for text preprocessing and similarity matching.

---

## Features

- Stores FAQs in a structured **JSON file**
- Preprocesses text using **NLTK** (tokenization and cleaning)
- Matches user queries with stored FAQs using **cosine similarity**
- Displays the most relevant answer as the chatbot response
- Easy to extend and update FAQ data

**Optional features (future scope):**

- Graphical user interface using `tkinter` or `streamlit`
- Intent classification using machine learning models
- Support for multiple domains or datasets

---

## Prerequisites

Before running this project, ensure the following are installed:

- **Python 3.7 or above**
- **pip (Python package manager)**
- Required Python libraries:
  - numpy
  - tensorflow
  - nltk
  - scikit-learn

Install all required libraries using:

```bash
pip install numpy tensorflow nltk scikit-learn
