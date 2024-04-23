# Domain-Ranking-Trend-Analysis

## Introduction
Built a data science tool to visualize the correlation between news articles and the change in domain rankings for the corresponding domain discussed in the article. Fine-tuned a pretrained Transformer Encoder (BERT) with a classification head that takes in a news article as input and outputs a linear classification corresponding to positive or negative short-term or long-term trends.

## Key Features
Leveraged the Tranco dataset (domain rankings) along with a news articles dataset (Huffpost) for the years 2019-2022. Integrated a fine-tuned Transformer model from HuggingFace for sentiment analysis of news article headlines. Used the spaCy library to scan for semantic similarity between news article headlines/descriptions and a predefined list of domain name search terms.

## Technology Stack / Libraries
Python
PyTorch
spaCy
Matplotlib
