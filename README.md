# Toxic-comment-classification-using-LSTM-and-LSTM-CNN

## Introduction
Online forums are meant to put forward our thoughts but some online comments contain explicit language which may hurt the readers and cause them to stop expressing themselves. ML algorithms are deployed to filter out the unruly language and protect internet users from becoming victims of online harassment and cyberbullying.

## About the problem and methodology

The data contains around 150,000 comments from social media and other online websites along with 6 labels such as Toxic, Severe Toxic, Obscene, Threat, Insult, and Identity Hate. Each comment may belong to any category or multiple categories or none. Basically, this is a multi-label classification problem. We clean the data and conduct excessive pre-processing after which we convert the comments into embeddings using fastText. We then make use of following 2 models:

Method 1 ( LSTM ) ---> LSTM can effectively preserve the characteristics of historical information in long text sequences, thus giving us better predictive power than normal deep neural network.

Method 2 ( LSTM & CNN ) ---> CNN can extract the local features of the text. Combining the LSTM and CNN neural network architectures helps us harness their combined capabilities.
