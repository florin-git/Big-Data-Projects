# Big Data Projects
This repository contains the main projects of the Big Data course I took in 2022.

## Locality Sensitive Hashing (LSH)
In this project I worked on about 500k Amazon reviews. The goal is to compute the cosine similarity between textual reviews, using the LSH technique. In general, given a similarity function, the compution of the 
pairwise similarity takes approximately $O(n^2)$ time, with $n$ being the number of elements. In contrast, LSH approximates the exact solution in linear time with a certain probability.

## Singular Value Decomposition (SVD)
In this simple notebook, I have analyzed the effectiveness of the SVD technique on images. Indeed, I computed the low-rank approximation of the same image to see how qualitative the result is when considering the approximated matrix instead of the original one. 

## Clustering for Topic Extraction
The goal of this project is to use dimensionality reduction techniques to perform clustering and keyword extraction from a collection of Amazon reviews, consisting of about 3M reviews. I used and compared different approaches, using K-Means, SVD and Random Projections. 