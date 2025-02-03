# Sentiment Analysis with Text Data

## Overview

This project focuses on performing sentiment analysis on textual data. The goal is to classify text based on sentiment (positive, negative, or neutral) using machine learning techniques. Specifically, the project utilizes **Recurrent Neural Networks (RNNs)**, which are highly effective in handling sequential data, such as text.

### Techniques Used

The project investigates various **word embeddings** that represent words as vectors of numbers, allowing the machine learning model to process and understand the text more effectively. The embeddings used in this project include:

- **Word2Vec**: Represents words by their context in a given text.
- **GloVe**: A method for creating vector representations of words based on global statistical information.
- **FastText**: A method that improves upon Word2Vec by considering subword information.

### Objective

The primary objective of this project is to evaluate how different embeddings affect the performance of sentiment analysis models and to explore the use of RNNs in this context.

## Repository Structure
- **`Sentiment_Analysis_RNN.ipynb`**: RNN-based sentiment analysis example.
- **`Sentimental_Analysis_Main.ipynb`**: Main notebook combining various methods.
- **`Sentiment_Analysis_FastText.ipynb`**: Implementation using FastText embeddings.
- **`Sentiment_Analysis_GLoVe.ipynb`**: Implementation using GLoVe embeddings.
- **`Sentiment_Analysis_Word2Vec.ipynb`**: Implementation using Word2Vec embeddings.
