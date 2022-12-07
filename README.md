# kmeans-from-scratch
This is a Python implementation of the k-means clustering algorithm using pandas, numpy, and scipy. The goal of this project was to gain experience implementing machine learning algorithms from scratch and to learn about the k-means algorithm.

Dependencies
To run this code, you will need to have the following Python packages installed:

pandas
numpy
scipy
Usage
To use the k-means algorithm, you will need to provide the following inputs:

data: a pandas DataFrame containing the data to be clustered. The DataFrame should contain only numerical columns.
k: the number of clusters to create.
num_iterations: the number of iterations to run the algorithm for.
The function will return the following outputs:

cluster_centers: a pandas DataFrame containing the coordinates of the cluster centers.
cluster_labels: a numpy array containing the cluster labels for each data point.

# Learnings
Implementing the k-means algorithm from scratch provided a deeper understanding of how the algorithm works and the challenges involved in optimizing it. Some key learnings from this project include:

- The importance of initializing the cluster centers properly in order to avoid suboptimal solutions.
- The need to carefully choose the number of iterations to run the algorithm for in order to avoid overfitting to the training data.
- The challenges of scaling the algorithm to handle large datasets.
Overall, this project was a valuable learning experience and provided a better understanding of the k-means algorithm and its applications in machine learning.



