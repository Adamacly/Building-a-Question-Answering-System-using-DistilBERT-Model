# Building a Question Answering System using DistilBERT Model

Question answering (QA) involves providing a correct answer to a question. If you've ever asked a smart assistant like Alexa, Siri, or Google about the weather, you’ve already used a QA system.

There are two main types of QA:

Extractive QA: Finds and pulls the answer directly from a given passage.

Abstractive QA: Understands the context and generates a new answer, rather than copying it word-for-word.

This guide will walk you through:

Training (fine-tuning) a DistilBERT model using the SQuAD dataset for extractive QA.

Using the trained model to answer questions based on a given text (inference).