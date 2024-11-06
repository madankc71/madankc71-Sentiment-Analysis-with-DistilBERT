# Sentiment Analysis with DistilBERT
=====================================

## Overview
------------

A simple project demonstrating sentiment analysis using a pre-trained DistilBERT model.

## Installation
------------

### Required Libraries

* **Transformers**: Install with `pip install transformers`
* **Torch**: Install with `pip install torch`
* **Torch.nn**: Install with `pip install torch.nn`

## Usage
-----

### Running the Project

1. Clone the repository.
2. Run `python sentiment_analysis.py`.

## Model Details
----------------

### Pre-trained Model

* **Model Name**: `textattack/distilbert-base-uncased-SST-2`
* **Number of Labels**: 2 (positive and negative sentiment)

## Code Structure
-----------------

### Key Functions

* **`load_model_and_tokenizer`**: Loads pre-trained model and tokenizer.
* **`predict_sentiment`**: Predicts sentiment for input texts.
* **`main`**: Runs the sentiment analysis pipeline.
