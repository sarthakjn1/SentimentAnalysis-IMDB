# Sentiment Analysis on IMDB Movie Reviews
## Dataset
Review Content: The reviews are in plain text, consisting of movie reviews written by users. These reviews vary in length and writing style, making the dataset a good testbed for text preprocessing, sentiment analysis, and text classification.

Balanced Dataset: The dataset contains an equal number of positive and negative reviews, making it balanced for binary classification tasks.

Positive reviews: 25,000

Negative reviews: 25,000

Review Length: The average length of reviews can vary, but some reviews are quite long (even exceeding 1,000 words). Typically, longer reviews tend to have more diverse opinions.

## Objective
Objective: Classify the sentiment of a movie review as either positive (label = 1) or negative (label = 0).

Number of Classes: 2 (Positive, Negative)

Dataset Size:
Training Set: 25,000 reviews

Test Set: 25,000 reviews

Total: 50,000 reviews

## Methodology
1. Build and train a feedforward neural network to perform sentiment analysis.
2. Use pretrained word embeddings like GloVe to initialize the word embeddings.
3. Evaluate Results on the Test set
