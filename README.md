# Natural-Language-Processing
Implementing natural language processing using python NLTK library and classify movie reviews.

### What is natural language processing?

Natural Language processing is an area of computer science and artificial intelligence concerned with interactions between computers and human(natural) languages,in particular how to program computers to process large amounts of natural data.

This rapidly improving area of artificial intelligence covers task as speech recognition ,natural language understanding and natural language generation.

#### This project consists of two parts

The first part consists of nltk function for tokenizing,speech tagging and chunking. I have tokenized words,used Punkt sentence tokenizer.
After tokenizing the words I have used Chunking(Grouping) on the text and predict the parts of speech using nltk's position tag function.
I used Chinking to remove some of the words from a Chunk that I didnot want.After that I used named entity recognition using nltk's named entity recognizer.


In the second part of this project I have made a simple text classifier to predict positive and negative movie reviews using a support vector classifier and nltk.I have imported the sklearn classifier from the scikit package and used the nltk package to prdict the accuracy.
The accuracy of the simple text classifier is 78.8%.
