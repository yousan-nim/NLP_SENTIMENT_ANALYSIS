# NLP_SENTIMENT_ANALYSIS

## Simple Sentiment Analysis
This tutorial covers the workflow of a PyTorch with torchtext project. We'll learn how to: load data, create train/test/validation splits, build a vocabulary, create data iterators, define a model and implement the train/evaluate/test loop. The model will be simple and achieve poor performance, but this will be improved in the subsequent tutorials.


## Upgraded Sentiment Analysis
Now we have the basic workflow covered, this tutorial will focus on improving our results. We'll cover: using packed padded sequences, loading and using pre-trained word embeddings, different optimizers, different RNN architectures, bi-directional RNNs, multi-layer (aka deep) RNNs and regularization.



## Faster Sentiment Analysis 
After we've covered all the fancy upgrades to RNNs, we'll look at a different approach that does not use RNNs. More specifically, we'll implement the model from Bag of Tricks for Efficient Text Classification. This simple model achieves comparable performance as the Upgraded Sentiment Analysis, but trains much faster.


## Convolutional Sentiment Analysis 
Next, we'll cover convolutional neural networks (CNNs) for sentiment analysis. This model will be an implementation of Convolutional Neural Networks for Sentence Classification.


## Multi-class Sentiment Analysis 
Then we'll cover the case where we have more than 2 classes, as is common in NLP. We'll be using the CNN model from the previous notebook and a new dataset which has 6 classes.


## Transformers for Sentiment Analysis 
Finally, we'll show how to use the transformers library to load a pre-trained transformer model, specifically the BERT model from this paper, and use it to provide the embeddings for text. These embeddings can be fed into any model to predict sentiment, however we use a gated recurrent unit (GRU).
