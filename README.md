# Intent-classification-NLP-2023


This paper focuses on the implementation of an NLP model for performing contextual emotion classification on a dialogue dataset from the famous TV show Friends. It aims at taking into account the context of the conversations for each sentence through a self-attention mechanism. In order to do so, we are going to build a hierarchical attention network that has a structure comparable to the one of a corpus of dialogues. Indeed, a dialogue is a conversation between two individuals who pronounce a sequence of sentences that have a specific signification in the context of the conversation. It thus has a hierarchical structure between the conversation, the sentences in the conversations, and the words contained in those sentences.

Formally, we want to capture a double context : first, words importance vary from one sentence or conversation to another, and secondly, not every sentence in a conversation are equally important regarding the context of the conversation

`https://raw.githubusercontent.com/AlexisVignard-hub/Intent-classification-NLP-2023/main/FinalNLP.ipynb`
