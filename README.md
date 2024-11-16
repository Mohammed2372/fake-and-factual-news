# Fake News Analysis and Classification

This project applies Natural Language Processing (NLP) and machine learning techniques to analyze and classify fake news articles. The goal is to explore various linguistic features and build effective models for fake news detection.

## Features
- **Data Analysis**: Understand the distribution and characteristics of fake vs. factual news.
- **Part-of-Speech (POS) Tagging**: Analyze word types used in news articles.
- **Named Entity Recognition (NER)**: Identify named entities in fake and factual news.
- **Text Preprocessing**: 
  - Text cleaning: Lowercasing, removing punctuation and stopwords.
  - Tokenization and n-gram generation.
- **Sentiment Analysis**: Compare sentiment distribution in fake and factual news.
- **Machine Learning Models**:
  - Logistic Regression
  - Support Vector Machines (SVMs)
- **Vectorization**: Use techniques like CountVectorizer or TF-IDF for text feature extraction.

## Dataset
The project uses a dataset containing labeled fake and factual news articles. The dataset is split into training and testing sets for model evaluation.

## Requirements
To run the project, ensure you have the following dependencies installed:
- Python (>= 3.7)
- Libraries:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `sklearn`
  - `nltk`
  - `spacy`

## Installation
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd fake_news_analysis
   ```
2. Install the required libraries

## Usage
1. Open the jupyter notebook:
   ```bash
   jupyter notebook fake_news_Project.ipynb
   ```
2. Run the cells sequentially to execute data preprocessing, analysis, and classification.

## Results
The notebook evaluates different models on the fake news dataset, providing insights into model accuracy and feature importance.
