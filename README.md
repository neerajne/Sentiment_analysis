# Sentiment Analysis System using PyTorch & RNN

An end-to-end Natural Language Processing (NLP) pipeline designed to classify user reviews as positive or negative using PyTorch and Recurrent Neural Networks (RNN) trained on the 50,000-row IMDB Dataset.

## Features
- **Comprehensive Text Preprocessing:** Cleaned raw text via lowercasing, HTML tag & URL removal, and punctuation filtering.
- **Feature Extraction:** Feature vectorization using TF-IDF.
- **Model Architecture:** Sequential Recurrent Neural Network (RNN) implemented in PyTorch for capturing context in text.
- **Performance:** Achieved **85% accuracy** on binary sentiment classification.

## Tech Stack
- **Language:** Python
- **Frameworks & Libraries:** PyTorch, NLTK, Scikit-learn, Pandas, NumPy, Matplotlib, Seaborn

## Dataset
- **Source:** IMDB Dataset (`IMDB Dataset.csv`) containing 50,000 movie reviews labelled for binary sentiment analysis.

## Usage
Open and run `RNN_for_sentimentanalysis.ipynb` in Jupyter Notebook or Google Colab to execute the text preprocessing pipeline, model training, and evaluation steps.
