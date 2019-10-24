# Tokenisation and Building N-Gram models in NLP
This project involves creating a tokenizer form scratch that is used to tokenize the lexemes that are  common in Natural Language Processing (e.g. words, names, urls, punctuation, currency, etc.) Whitespaces are ignored in general in the text to be tokenised. The tokeniser was then used to create N-Gram language models on different training corpora. 
The tokeniser outputs each lexeme seperated by a space which can then be directed to a file to be saved if required.
Various N-Gram Models created on the training corpora were 4-Gram model and 6-Gram model. Kneser-Ney smoothing was also applied. The models also had a back-off mechanism and the both models can back-off till unigram probabilities if required. 
Entropy and perplexity of the training corpora was also calculated.
