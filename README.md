# Entri-Elevate-Unsupervised-Learning

# Iris Clustering Project

## Overview

This project demonstrates the application of clustering techniques to the Iris dataset, a well-known dataset in machine learning. The goal is to implement and analyze two clustering algorithms: KMeans and Hierarchical Clustering, and evaluate their effectiveness in grouping the Iris flowers into distinct clusters.

## Dataset

The Iris dataset, available in the `sklearn` library, consists of 150 samples of iris flowers, each described by four features:

- **Sepal Length**
- **Sepal Width**
- **Petal Length**
- **Petal Width**

There are three species of Iris flowers in the dataset, but since this is an unsupervised learning problem, the species labels are not used in clustering.

## Project Structure

The project is organized into the following sections:

1. **Loading and Preprocessing**
    - Load the Iris dataset.
    - Preprocess the data by removing the species labels (target variable) to focus on clustering the features.

2. **Clustering Algorithm Implementation**
    - **KMeans Clustering**
        - Description of how KMeans clustering works.
        - Justification for using KMeans on the Iris dataset.
        - Implementation of KMeans clustering.
        - Visualization of the resulting clusters.
    - **Hierarchical Clustering**
        - Description of how Hierarchical clustering works.
        - Justification for using Hierarchical clustering on the Iris dataset.
        - Implementation of Hierarchical clustering.
        - Visualization of the resulting clusters.

## Visualization
The notebook includes visualizations to help understand how the clustering algorithms group the data. These include scatter plots that display the clusters formed by KMeans and Hierarchical clustering.

## Conclusion
This project provides a comparison between KMeans and Hierarchical clustering on the Iris dataset, offering insights into the natural groupings within the data. Both clustering techniques can effectively group the data, but each has its own strengths and weaknesses depending on the dataset and the problem at hand.
