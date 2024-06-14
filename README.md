# Sentiment Analysis with LSTM and GloVe

## Overview

This project employs Long Short-Term Memory (LSTM) networks and GloVe (Global Vectors for Word Representation) embeddings to perform sentiment analysis on movie reviews. It classifies the sentiment of text data into positive or negative categories.

## Prerequisites

Ensure you have Python 3.8 or higher installed. The project requires PyTorch, NumPy, Pandas, and Matplotlib. Setup a Conda environment to manage these dependencies:

```bash
conda create -n sentiment_analysis python=3.8
conda activate sentiment_analysis
conda install pytorch torchvision cudatoolkit=10.2 -c pytorch
conda install numpy pandas matplotlib
```
