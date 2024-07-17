# YouTube Comment Analysis

This repository contains code and methodology for a comprehensive analysis of YouTube comments. The project aims to identify sentiment, detect hate speech, and discover thematic structures within the comments using machine learning and natural language processing techniques.

## Project Overview

The goal of this project is to provide insights into the public sentiment expressed in YouTube comments and to detect any prevalent hate speech, with the additional objective of clustering comments to discover underlying themes.

## Features

- **Sentiment Analysis**: Determine the sentiment of comments as positive or negative.
- **Hate Speech Detection**: Identify and flag comments that contain hate speech.
- **Clustering**: Group similar comments together to identify common themes.
- **Dimensionality Reduction**: Use an autoencoder to reduce the dimensionality of text data.
- **Visualization**: Visualize the clustering results to better understand the data.

## Data

The dataset consists of YouTube comments extracted using the YouTube Data API. Note that you will need API access to fetch new comments.

## Methods

### Data Preprocessing

Text data is cleaned, tokenized, and transformed into a format suitable for NLP tasks.

### Sentiment Analysis

Sentiment is analyzed using a pre-trained BERT model from Hugging Face's `transformers` library.

### Hate Speech Detection

Hate speech is detected using a custom-trained BERT model.

### Clustering

Comments are embedded using an autoencoder and clustered via K-Means to identify themes.

### Visualization

Results from clustering are visualized using PCA and t-SNE for easy interpretation of the data's structure.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your features or corrections.
