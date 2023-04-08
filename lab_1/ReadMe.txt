Word2Vec and Spam Detector with Gensim

This notebook showcases how to use the Word2Vec library in Gensim to pretrain embeddings on text data, 
and then use these embeddings to train a spam detector model. We also explore intrinsic and extrinsic evaluation methods for the embeddings.

Contents

Word2Vec: we start by introducing the Word2Vec algorithm and showing how to use it in Gensim to train word embeddings on a corpus of text.

Spam detector: we then use the pre-trained embeddings to train a spam detector model, which takes as input a text message and outputs a binary 
classification of spam or not spam.

Evaluation: we evaluate the quality of the embeddings using intrinsic evaluation methods such as word similarity and analogy tasks, 
as well as extrinsic evaluation by measuring the accuracy of the spam detector model.
