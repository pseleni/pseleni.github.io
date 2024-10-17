---
title: "Efficient Time-Series Clustering through Sparse Gaussian Modeling"
collection: publications
category: journals
# permalink: /publication/tsClustering
excerpt: 'with Dimitris Fotakis, Panagiotis Patsilinakos and Michalis Xefteris'
date: 2024-01-30
venue: 'Algorithms, 2024'
# slidesurl: ''
codeurl: 'https://github.com/pseleni/ts_clustering'
paperurl: 'https://www.mdpi.com/1999-4893/17/2/61/pdf?version=1706674843'
citation: 'Fotakis D, Patsilinakos P, Psaroudaki E, Xefteris M. (2024). &quot;Efficient Time-Series Clustering through Sparse Gaussian Modeling.&quot; <i>Algorithms.</i> 17(2):61. https://doi.org/10.3390/a17020061'
bib: './../files/tsclustering.bib'
---

In this work, we consider the problem of shape-based time-series clustering with the widely used Dynamic Time Warping (DTW) distance. We present a novel two-stage framework based on Sparse Gaussian Modeling. In the first stage, we apply Sparse Gaussian Process Regression and obtain a sparse representation of each time series in the dataset with a logarithmic (in the original length T) number of inducing data points. In the second stage, we apply k-means with DTW Barycentric Averaging (DBA) to the sparsified dataset using a generalization of DTW, which accounts for the fact that each inducing point serves as a representative of many original data points. The asymptotic running time of our Sparse Time-Series Clustering framework is Ω(T2/log2T) times faster than the running time of applying k-means to the original dataset because sparsification reduces the running time of DTW from Θ(T2) to Θ(log2T). Moreover, sparsification tends to smoothen outliers and particularly noisy parts of the original time series. We conduct an extensive experimental evaluation using datasets from the UCR Time-Series Classification Archive, showing that the quality of clustering computed by our Sparse Time-Series Clustering framework is comparable to the clustering computed by the standard k-means algorithm.