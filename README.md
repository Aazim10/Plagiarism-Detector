# Plagiarism-Detector
First preprocessed the documents by normalizing, removing stopwords, punctuations, special characters and then lemmatizing each word in the document
Then generated Doc Vectors by averaging word vectors of each word in document. The word vectors were extracted using Google Word2Vec.
Then calculated cosine similarity to compare each pair of documents.
