# MS4610: Introduction to Data Analytics

The repository contains code for MS4610: Introduction to Data Analytics review clustering project.

Natural Language Processing is the application of data-driven techniques to interpret natural language and speech. The course project presents various algorithms, unsupervised techniques and approaches to perform hierarchical clustering of text data. It aims to serve as a guide to clustering textual data of any kind using the listed algorithms. The text data consists of various product reviews collected from Amazon, Walmart, CVS and Influenster. 

The report starts with an introduction to the given dataset, followed by exploratory data analysis of the same. Thereafter, text cleaning techniques like removal of punctuation, special characters, emojis, stop words, spaces, tabs, etc including converting all words to lowercase is carried out. Lemmatization is performed on this cleaned data to extract the root word and retain semantic similarity in reviews. These reviews are then encoded to vectors using various encoding techniques, each of which is explained and weighed against it’s advantages and disadvantages. The vectors so obtained are then sent into different clustering models to obtain meaningful interpretation and topic modelling. Implementations of models like TextRank, LDA, LSA, NMF, HDBSCAN, etc are explored.
