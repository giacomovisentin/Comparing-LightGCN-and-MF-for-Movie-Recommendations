# Comparing-LightGCN-and-MF-for-Movie-Recommendations
Recommendation systems personalize content across industries like e-commerce and streaming. Traditional methods like Matrix Factorization predict user preferences, while Graph Neural Networks (GNNs) model complex relationships. This project compares these approaches in recommending movies.

## Datasets: 
you can find the dataset we used in https://grouplens.org/datasets/movielens/

# ABSTRACT of the report
Recommendation systems have become an integral part of various industries, including e-commerce, streaming services, and social media, by providing personalized content and product suggestions to users. Traditional recommendation systems rely on techniques like Matrix Factorization, which decomposes user-item interactions to predict preferences. Recently, Graph Neural Networks (GNNs) have gained attention for their ability to model complex relationships in data, especially in user-item interaction networks. This project aims to compare the performance and suitability of Matrix Factorization and GNN-based approaches for recommendation tasks,  by observing how each technique recommends movies.

# CONCLUSIONS of the report
The objective of this report was not to compare the best Matrix Factorization (MF) model with the best graph neural network (GNN). Instead, our aim was to evaluate whether, in general, a GNN could outperform an MF model in the context of recommendation systems. For this purpose, we selected two well-known and widely recognized models for comparison.
The results show that the GNN model significantly outperforms the MF model. This can primarily be attributed to how GNNs represent users and items as nodes in a bipartite graph, effectively leveraging both direct and indirect relationships to create more informative embeddings. In contrast, MF approaches treat user-item interactions as entries in a simple interaction matrix, neglecting the underlying topology of the data.
A key advantage of GNNs lies in their ability to propagate information across the graph. This allows for multi-level connections, for instance a user can be linked to a movie not only because they directly rated it but also because similar users have rated it. By exploiting the graph's topology, GNNs can capture richer relational patterns, resulting in a significant improvement in recommendation system performance.
In conclusion, leveraging the graph structure and propagating information through it proves to be a highly effective strategy for enhancing recommendation systems.
