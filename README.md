# classifying-document
This project is part of the IBM AI Engineering Professional Certificate and focuses on using Natural Language Processing (NLP) and PyTorch to build a document classification system. The goal is to automate the categorization of news articles into predefined topics — a critical step in organizing massive archives of historical documents in media or publication contexts.

# Project Overview

Imagine working for a major newspaper or magazine with decades of archived articles. Manually sorting these articles by topic is labor-intensive and inefficient. This project demonstrates how to automate this process using machine learning.

You will:

Use TorchText to load and preprocess a dataset of news articles.

Build and train a neural network classifier using PyTorch.

Use a DataLoader for efficient batching and shuffling of data during training.

Evaluate model performance on unseen data.

# Technologies Used

Python 3

PyTorch

TorchText

Natural Language Processing (NLP)

Jupyter Notebook

# Dataset

The dataset consists of labeled news articles, where each article belongs to a particular topic/class. The exact dataset is loaded via torchtext.datasets, which streamlines preprocessing and ensures compatibility with PyTorch pipelines.
