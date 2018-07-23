# Learning Clustering BahasaIndonesia Language

## Source Code

http://brandonrose.org/clustering

## Data sources

1. [Kompas online collection](http://ilps.science.uva.nl/ilps/wp-content/uploads/sites/6/files/bahasaindonesia/kompas.zip).
   This corpus contains [Kompas online](http://www.kompas.com/) news articles from 2001-2002. See
   [here](http://ilps.science.uva.nl/resources/bahasa/) for more info and citations.
1. [Tempo online collection](http://ilps.science.uva.nl/ilps/wp-content/uploads/sites/6/files/bahasaindonesia/tempo.zip).
   This corpus contains [Tempo online](https://www.tempo.co/) news articles from 2000-2002. See
   [here](http://ilps.science.uva.nl/resources/bahasa/) for more info and citations.
   
   
## Step

1. tokenizing and stemming each article (Bahasa Indonesia)
1. transforming the corpus into vector space using tf-idf
1. calculating cosine distance between each document as a measure of similarity
1. clustering the documents using the k-means algorithm
1. using multidimensional scaling to reduce dimensionality within the corpus
1. plotting the clustering output using matplotlib and mpld3
1. conducting a hierarchical clustering on the corpus using Ward clustering
1. plotting a Ward dendrogram
1. topic modeling using Latent Dirichlet Allocation (LDA)


## Library
