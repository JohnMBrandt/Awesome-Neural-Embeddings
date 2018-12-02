# Awesome-Neural-Embeddings

A curated list of information and tutorials about word and sentence embeddings

## Overview / General

[The Current Best of Universal Word Embeddings and Sentence Embeddings](https://medium.com/huggingface/universal-word-sentence-embeddings-ce48ddc8fc3a) - Thomas Wolf

Gentle introduction to FastText, ELMo embeddings, Universal Sentence Encoder, Skip-Thoughts, and Quick-Thoughts all in one place. No theory or math is covered, but provides a general overview of motivations and applications.

[When to use pretrained embeddings](https://machinelearningmastery.com/develop-word-embeddings-python-gensim/) - Jason Browniee

This rather long tutorial covers GloVe and Word2Vec implementation in Python with special attention to the variation between using a pre-trained embedding matrix and training one on a domain-specific corpus. This is a trade-off that is frequently assessed when developing downstream applications.

[Word embedding trends](http://ruder.io/word-embeddings-2017/) - Sebastian Ruder

An incredibly well-researched discussion on the future trends of word embeddings with almost 60 references. This post discusses phrase-level embeddings, model bias, the temporal dimension of word meaning, domain-specific embeddings, transfer learning, and context-specific embeddings.

[Polysemy in Word Embeddings](https://medium.com/@jegasingamjeyanthasingam/word-embedding-to-polysemy-embedding-17274ab98418) - Jegasingam Jeyanthasingam

Explains the inability of GloVe and Word2vec to model polysemy (where a single word can take on multiple meanings). As the major drawback to word embeddings, developing a strong understanding of polysemy and how to address the issues it poses is tantamount.

[History of embeddings](https://towardsdatascience.com/3-silver-bullets-of-word-embedding-in-nlp-10fa8f50cc5a) - Edward Ma

## Word Embeddings

[Word2Vec tutorial](http://mccormickml.com/2016/04/19/word2vec-tutorial-the-skip-gram-model/) - Chris McCormick

Christ McCormick's three-part tutorial for word2vec is the best way to get started learning about word embeddings. The intuition for the skip gram model is explained with diagrams, and part II and III of the tutorial cover negative sampling, subsampling, and n-gram bundling. 

[GloVe tutorial](http://mlexplained.com/2018/04/29/paper-dissected-glove-global-vectors-for-word-representation-explained/)

This paper disection explains the math behind GloVe. This is very important to understand because GloVe is cast as a weighted-least squares objective. The blog discusses how gloVe compares with Word2Vec in terms of training time and accuracy.

[ElMo embedding tutorial](https://github.com/allenai/allennlp/blob/master/tutorials/how_to/elmo.md) - Allen AI

Tutorial for implementing pre-trained ELMo embeddings from the algorithm's authors. Shows how to use it with Tensorflow Hub as well as PyTorch. Discusses hyperparameter settings and demonstrates how to reproduce the code from the original paper.

[MUSE Multilingual Embeddings](https://code.fb.com/ml-applications/under-the-hood-multilingual-embeddings/) - Facebook

MUSE is a multilingual approach to word embeddings developed by Facebook research. This post is very interesting in that it shows how the architecture is used live on Facebook's site, and also discusses what is being researched as MUSE's replacement.

[FastText](https://towardsdatascience.com/fasttext-under-the-hood-11efc57b2b3) - Nishan Subedi

A quick introduction to the math and theory behind FastText, as well as thoughts on best practices for training and structuring data.

## Sentence Embeddings

[Sent2Vec](https://rare-technologies.com/sent2vec-an-unsupervised-approach-towards-learning-sentence-embeddings/) - Prerna Kashyap

Quick GenSim implementation of sent2vec, as well as information about its history and a fast-paced overview of how it works. 

[Infersent](https://yashuseth.blog/2018/08/06/infersent-supervised-learning-of-sentence-embeddings/) - Seth Yashu

In addition to explaining the infersent algorithm, this blog post is a good starting point for the reader who may be unfamiliar with LSTM, GRU, pooling, and attention. This blog post does an exceptional job of explaining how individual weights are calculated and why they are important for making the sentence embeddings useful.

[Skip thoughts](https://medium.com/@sanyamagarwal/my-thoughts-on-skip-thoughts-a3e773605efa) - Sanyam Agarwal

Tensorflow implementation of skip thougths algorithm and diagramatic and conceptual explanation of the encoder-decoder model. This blog post covers the advantages and disadvantages of the algorithm in detail.

[Doc2Vec](https://medium.com/scaleabout/a-gentle-introduction-to-doc2vec-db3e8c0cce5e) - Gidi Shperber

A very well-explained introduction to Doc2vec, the sentence and document level implementation of word2vec. The blog post uses the original diagrams from the paper, and includes a quick code demo using gensim.
 
