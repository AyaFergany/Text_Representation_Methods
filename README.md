# Text_Representation_Methods

Text representation methods are applied to convert text data into a numerical format that machine learning algorithms can process. This is essential because algorithms require numerical input to perform tasks such as classification, sentiment analysis, or translation. Methods like *Bag of Words, TF-IDF, word embeddings.*

**1.  Bag of words**

Each word in the text is considered a feature, and the number of times a particular word appears in the text is used to represent the importance of that word in the text. 
BOW keeps track of the frequency of each word in a text, disregarding grammar and word order.

**2.  TF-IDF**
   
TF-IDF is better than BoW since it interprets the importance of a word in a document. 
TF-IDF weighs words based on how often they appear in a document (the term frequency) and how common they are across all documents (the inverse document frequency).

**3.   Word to vector**
   
Word2Vec is a shallow neural network model that learns to represent words in a continuous vector space.
Developed by researchers at Google in 2013, Word2Vec aims to capture semantic relationships between words based on their co-occurrence patterns in a large corpus of text data.

Word2Vec employs two main architectures: *Continuous Bag of Words (CBOW) and Skip-gram*.

**1. CBOW** predicts the target word based on its context (surrounding words). It uses the context words as input to predict the target word. This architecture is efficient for smaller datasets and frequent words.

**2. Skip-gram** predicts the context words given a target word. It uses the target word as input to predict the context words. This architecture performs well with larger datasets and infrequent words.








