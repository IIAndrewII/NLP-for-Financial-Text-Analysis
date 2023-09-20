# NLP for Financial Text Analysis
Predict stock price movements from financial texts:

This repository contains the code and data for an advanced natural language processing (NLP) project that applies state-of-the-art techniques like BERT to financial texts such as earnings calls, analyst reports, and news articles. The goal is to provide valuable insights for investment analysis and decision-making.

## Dataset

The dataset used for this project is the [Motley Fool Scraped Earnings Call Transcripts] from Kaggle, which contains over 10,000 transcripts of quarterly earnings calls from US companies from 2009 to 2020. Each transcript has a label indicating whether the stock price increased or decreased in the next quarter after the call.

## Tasks

The project consists of the following tasks:

1. Fine-tune a BERT NLP model on the earnings call dataset to predict whether the stock price will increase or decrease in the next quarter based on the transcript text. Evaluate the model's accuracy.
2. Build a Named Entity Recognition model using BERT to extract key financial metrics like revenue, expenses and profit from earnings call transcripts. Evaluate against a labeled subset.
3. Construct a sentiment analysis model using BERT to determine management sentiment (positive/negative) from the transcript text. Assess against human annotations.
4. Design a pipeline architecture that ingests new earnings call transcripts, passes them through the NLP models to extract key phrases, metrics, and sentiment, and makes an investment recommendation based on the outputs.


## Installation

To run this project, you will need Python 3.7 or higher and the following libraries:

- [PyTorch](https://pytorch.org/)
- [Transformers](https://huggingface.co/transformers/)
- [Pandas](https://pandas.pydata.org/)
- [NumPy](https://numpy.org/)

You can install them using pip or conda.
