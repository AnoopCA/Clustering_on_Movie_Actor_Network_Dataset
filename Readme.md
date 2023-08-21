Grouping Similar Movies and Actors Using Clustering:
This GitHub repository contains code to group similar movies and actors using clustering techniques. The project utilizes network analysis, node embedding, and clustering algorithms to identify and visualize clusters of similar movies and actors. The code is implemented in Python and makes use of various libraries such as NetworkX, StellarGraph, scikit-learn, numpy, pandas, matplotlib, gensim, and TSNE.

Installation:
To run this project, you need to install the required libraries. You can do this using the following commands:
pip install networkx==2.3
pip install stellargraph

Usage:
Import the necessary libraries and packages.
Read the data into a DataFrame.
Create a bipartite graph with movie and actor nodes and edges from the imported data.
Perform random walks on the graph to generate node embeddings using StellarGraph.
Train a Word2Vec model to featurize the node embeddings.
Split the featurized vectors into separate sets for actors and movies.
Define functions to calculate clustering costs for actors and movies.
Calculate the costs and determine the optimal number of clusters.
Apply KMeans clustering to group similar actors and visualize the results using TSNE.

Steps:
Install required libraries.
Import libraries and packages.
Read and preprocess the dataset.
Perform random walks and generate node embeddings.
Train Word2Vec model for featurization.
Split featurized vectors for actors and movies.
Calculate clustering costs for actors and movies.
Determine optimal number of clusters.
Apply clustering algorithm for actors and visualize clusters.

Contributing:
Contributions to this project are welcome! Feel free to open issues or pull requests for bug fixes, improvements, or additional features.

License:
No specific license is provided for this project.