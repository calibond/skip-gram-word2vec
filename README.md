Skip-gram Word Embeddings

Overview
This project implements the Skip-gram model, a neural network-based approach for learning word embeddings. Skip-gram is a technique from the Word2Vec framework, designed to predict context words given a target word. The model is trained on a corpus to generate dense vector representations of words, capturing semantic relationships between them.

Features
Preprocessing: Tokenization and creation of training data for the Skip-gram model.
Model Implementation: A neural network using embeddings to train on word relationships.
Training: Optimizing the model using stochastic gradient descent.

Evaluation: Visualizing learned word vectors and exploring their relationships.

Installation: To run this notebook, you need Python and the following libraries: pip install numpy pandas torch matplotlib nltk

Usage
Open the Jupyter Notebook:
jupyter notebook SkipGram.ipynb
Run each cell sequentially to preprocess data, build the Skip-gram model, and train it on text data.
Explore the learned embeddings using visualization techniques.

Results
The trained Skip-gram model produces word embeddings that can be used for:
Semantic similarity tasks
Text classification
Information retrieval

Practice For: 
Experimenting with different corpus sizes and types
Using pretrained embeddings for comparison
Implementing negative sampling for efficiency
