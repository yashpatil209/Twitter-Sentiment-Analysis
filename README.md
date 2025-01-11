# Twitter Sentiment Analysis

## Overview

This project uses natural language processing (NLP) and machine learning techniques to perform sentiment analysis on tweets. The goal is to classify tweets as either positive or negative. The model is trained using the Naive Bayes classifier and evaluated on a test set. Visualizations of word clouds for positive and negative sentiments are also generated to better understand the words associated with each sentiment.

## Features

- **Data Preprocessing**: Cleans the text data by removing stopwords, URLs, mentions, and hashtags.
- **Sentiment Classification**: Classifies tweets as "Positive" or "Negative" using the Naive Bayes classifier.
- **Word Cloud Generation**: Generates word clouds for positive and negative tweets to visually analyze sentiment-related terms.
- **Model Evaluation**: Evaluates the model’s performance by counting the number of correct classifications for both positive and negative tweets.

## Technologies Used

- **Python**: The primary programming language.
- **Pandas**: For data manipulation and preprocessing.
- **Scikit-learn**: For machine learning model building and evaluation.
- **NLTK**: For text processing, stopword removal, and feature extraction.
- **WordCloud**: To generate visualizations for word clouds.
- **Matplotlib**: For plotting and visualizing results.



## Example Output

- **Word Cloud**: Visualizations displaying the most frequent words in positive and negative tweets.
- **Model Evaluation**: The accuracy of the model is displayed, showing the number of correctly classified positive and negative tweets.

    ```bash
    [Negative]: 867/819
    [Positive]: 222/67
    ```

## Contributing

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Commit your changes.
4. Push your changes and create a pull request.

## Acknowledgements

- [NLTK](https://www.nltk.org/) for text processing and stopword removal.
- [Scikit-learn](https://scikit-learn.org/) for machine learning model training.
- [WordCloud](https://github.com/amueller/word_cloud) for generating word cloud visualizations.
- [Matplotlib](https://matplotlib.org/) for plotting and visualizations.
