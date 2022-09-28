# MS4610: Introduction to Data Analytics

The repository contains code for MS4610: Intorduction to Data Analytics review clustering project.

Natural Language Processing is application of data-driven techniques to interpret natural lan-
guage and speech. Text Analysis in specific uses Machine Learning to extract information from

text data. The following pages present various algorithms, unsupervised techniques and ap-
proaches to perform hierarchical clustering of text data.This study aims to serve as a guide to

clustering textual data of any kind using the listed algorithms.
The text data consists of various product reviews collected from Amazon, Walmart, CVS and
Influenster. The report starts with an introduction to the given dataset, followed by exploratory
data analysis of the same.
Thereafter, text cleaning techniques like removal of punctuation, special characters, emojis,

stop words, spaces, tabs, etc including converting all words to lowercase is carried out. Stem-
ming and Lemmatization is performed on this cleaned data to extract the root word and retain

semantic similarity in reviews.
These reviews are then encoded to vectors using various encoding techniques, each of which is
explained and weighed against it’s advantages and disadvantages.The vectors so obtained are

then sent into different clustering models to obtain meaningful interpretation and topic mod-
elling. Implementations of models like TextRank, LDA, LSA, NMF, HDBSCAN, etc are ex-
plored.
