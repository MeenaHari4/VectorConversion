 1. Setup and Data Preparation:- Import necessary libraries: pandas, numpy, nltk, sklearn, gensim, matplotlib, seaborn.- Load the dataset: Choose a dataset for embedding generation.- Preprocess the text data: Perform cleaning, tokenization, stop-word removal, and other
 preprocessing steps.
 2. Bag of Words (BoW):- Create a BoW representation: Use `CountVectorizer` from sklearn to convert text into a
 matrix of word counts.- Analyze the BoW matrix: Examine the sparsity and interpret the word frequencies.
3. TF-IDF:- Apply TF-IDF transformation: Use `TfidfVectorizer` to generate TF-IDF features from the text
 data.- Interpret TF-IDF scores: Analyze how TF-IDF weighs different words in the dataset.
 4. Word2Vec:- Train a Word2Vec model: Use Gensim's `Word2Vec` to train a model on the dataset.- Extract word vectors: Obtain vector representations for words and visualize them.
 5. GloVe:- Use pre-trained GloVe embeddings: Load GloVe vectors and map words in the dataset to
 their corresponding embeddings.- Train a GloVe model (optional): Use the GloVe package to train embeddings if desired.
 6. FastText:- Train a FastText model: Use Gensim’s `FastText` to train embeddings that consider subword
 information.- Analyze FastText embeddings: Compare them with Word2Vec and GloVe embeddings
