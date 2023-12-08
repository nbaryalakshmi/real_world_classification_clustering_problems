# real_world_classification_clustering_problems
Machine Learning Algorithms for Solving Real-World Classification and Clustering Problems

This paper focuses on how similar documents from a large text corpus can be categorized or grouped together by applying machine learning algorithms. The bag of words dataset used for this project is downloaded from UCI Machine Learning Repository. Since the dataset is not labeled, two clustering algorithms are applied to cluster the documents into different groups. Data labeling for around thousand records are done manually and two classification algorithms are applied to this dataset. The data preparation and machine learning algorithms are implemented using python language, nltk libraries and scikit-learn machine learning libraries.

The dataset for this project is downloaded from UCI Machine Learning Repository. The dataset contains 299752 New York Times news articles, and the data is already in cleaned form by performing tokenization and removal of stopwords. This dataset has no class labels. The cleaned data is provided in two files named ‘docword.nytimes.txt’ and ‘vocab.nytimes.txt’, where the first file contains number of times each word occurs in each document and the second file is the vocabulary file which lists all the words that appear in the document collection.

The format of the ‘docword.nytimes.txt’ contains three header lines followed by document id (docID), word id (wordID) and word count (count). The three header lines will be omitted. The data format looks like below:

#D

#W

#NNZ

#docID wordID count

#docID wordID count

#...

#...

#docID wordID count

#docID wordID count

Each line in ‘vocab.nytimes.txt’ contains a unique word, where the line number is equal to word id (wordID).



