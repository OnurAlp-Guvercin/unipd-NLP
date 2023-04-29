Transition-Based Dependency Parsing with Neural Networks
This repository contains an implementation of transition-based dependency parsing using the arc-standard model augmented with neural networks for contextual word embeddings and action selection.

Overview
Dependency parsing is the task of analyzing the grammatical structure of a sentence to identify the relationships between words. The arc-standard model is a popular method for implementing dependency parsers that uses a transition-based approach.

This implementation adds neural machinery to the arc-standard model for contextual word embeddings and action selection, using the following features:

LSTM representation for stack tokens
MLP for next transition classification, based on two top-most stack tokens and first token in the buffer
Training under static oracle
This implementation disregards arc labels in dependency trees in order to keep the presentation simple.

The implementation is based on the following paper:

Kiperwasser and Goldberg, Simple and Accurate Dependency Parsing Using Bidirectional LSTM Feature Representations. Transactions of the Association for Computational Linguistics, Volume 4, 2016.

Note that the original paper uses a different model called arc-hybrid.

References
Kiperwasser and Goldberg, Simple and Accurate Dependency Parsing Using Bidirectional LSTM Feature Representations. Transactions of the Association for Computational Linguistics, Volume 4, 2016.
Chen and Manning, A Fast and Accurate Dependency Parser using Neural Networks. Proceedings of the 2014 Conference on Empirical Methods in Natural Language Processing (EMNLP), 2014.

