# News Headline Classification

## Overview
This project uses Natural Language Processing (NLP) techniques and a Logistic Regression model to classify news headlines into one of four categories:
- World
- Sports
- Business
- Sci/Tech

---

## Model Details
- **Vectorizer**: TF-IDF (Term Frequency-Inverse Document Frequency)
- **Classifier**: Logistic Regression
- **Text Preprocessing**:
  - Text Normalization
  - Tokenization
  - POS Tagging
  - Stopword Removal
  - N-gram Modeling

---

## Data Source
- **Dataset**: AG News Dataset
- **Link**: [https://www.kaggle.com/datasets/amananandrai/ag-news-classification-dataset]
---

## Environment Setup

1. **Clone the repository**:
   ```bash
   git clone https://github.com/PROFESSOR-GE0/NewsClassifier.git
   cd NewsClassifier
   
## How to Run the Code
- Launch Jupyter Notebook:
  - jupyter notebook
- Open NewsClassifier.ipynb
- Run all cells from top to bottom to:
  - Load and preprocess the dataset
  - Train the Logistic Regression model
  - Evaluate accuracy, precision, recall, F1-score
  - Test with sample input


