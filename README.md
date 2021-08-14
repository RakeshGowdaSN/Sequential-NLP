# Sequential-NLP

## Part - 1 (Sentiment Analysis)
• DOMAIN: Digital content and entertainment industry

• CONTEXT: The objective of this project is to build a text classification model that
analyses the customer's sentiments based on their reviews in the IMDB database. The
model uses a complex deep learning model to build an embedding layer followed by
a classification algorithm to analyse the sentiment of the customers.

• DATA DESCRIPTION: The Dataset of 50,000 movie reviews from IMDB, labelled by
sentiment (positive/negative). Reviews have been preprocessed, and each review is
encoded as a sequence of word indexes (integers). For convenience, the words are
indexed by their frequency in the dataset, meaning the for that has index 1 is the
most frequent word. Use the first 20 words from each review to speed up training,
using a max vocabulary size of 10,000. As a convention, "0" does not stand for a
specific word, but instead is used to encode any unknown word.

• PROJECT OBJECTIVE: Build a sequential NLP classifier which can use input text
parameters to determine the customer sentiments.

## Part - 2 (Sarcasm Detection)
• DOMAIN: Social media analytics

• CONTEXT: Past studies in Sarcasm Detection mostly make use of Twitter datasets collected
using hashtag based supervision but such datasets are noisy in terms of labels and
language. Furthermore, many tweets are replies to other tweets and detecting sarcasm in
these requires the availability of contextual tweets.In this hands-on project, the goal is to
build a model to detect whether a sentence is sarcastic or not, using Bidirectional LSTMs.

• DATA DESCRIPTION:
The dataset is collected from two news websites, theonion.com and huffingtonpost.com.
This new dataset has the following advantages over the existing Twitter datasets:
Since news headlines are written by professionals in a formal manner, there are no spelling mistakes and
informal usage. This reduces the sparsity and also increases the chance of finding pre-trained embeddings.
Furthermore, since the sole purpose of TheOnion is to publish sarcastic news, we get high-quality labels with
much less noise as compared to Twitter datasets.
Unlike tweets that reply to other tweets, the news headlines obtained are self-contained. This would help us in
teasing apart the real sarcastic elements
Content: Each record consists of three attributes:
is_sarcastic: 1 if the record is sarcastic otherwise 0
headline: the headline of the news article
article_link: link to the original news article. Useful in collecting supplementary data

• PROJECT OBJECTIVE: Build a sequential NLP classifier which can use input text parameters
to determine the customer sentiments.
