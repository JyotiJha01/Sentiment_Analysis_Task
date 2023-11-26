# Sentiment_Analysis_Task

Model Architecture:

The model architecture used in this implementation is based on DistilBERT, a smaller and computationally more efficient version of the BERT (Bidirectional Encoder Representations from Transformers) model. DistilBERT retains much of BERT's performance while requiring fewer computational resources. The sequence classification head is added to the DistilBERT base to adapt the model for sentiment analysis on the IMDb dataset. The choice of the sequence classification head with two output labels ("NEGATIVE" and "POSITIVE") is suitable for binary sentiment classification.

Choice of Dataset:

The IMDb dataset is chosen for this implementation. It is a widely used dataset in natural language processing for sentiment analysis tasks. The dataset consists of movie reviews labeled as either positive or negative based on the sentiment expressed in the text. The goal is to train a model to classify these reviews into positive or negative sentiments.
