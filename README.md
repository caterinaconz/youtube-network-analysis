# youtube-network-analysis

In this repository you can find my team's work for our Machine Learning for Network Sciences course project.
\
\
\
The aim of this project was to analyze YouTube complex network using graph-based method, exploring its features, performing link prediction, and applying Leiden Algorithm to identify community structures.
Some details:

* Each video is considered as a node of an undirected graph, an edge exists between video A and video B if B is in the related videos section of A. 
* A systematic comparison of several metrics for link prediction is done, computing for each metric the coefficient of the logistic regression, the accuracy score and the F1-score of the prediction. 
* In particular, we showed that neighbor-based and social theory-based features result in the highest accuracy and F1-score, with the number of common neighbors reaching alone a 96\% F1-score.
* Then, we proceeded using Leiden algorithm for community detection to reveal the hidden relations among the nodes in the network. 
* After identifying the communities we analysed the type of videos in each of them, finding that in the majority of cases in one community of related videos several categories can be found, and that creators generally participate in just one community of related videos.

\
\
\
*Contributors:*

Abdelbar, Sarah \
Conz, Caterina \
Moneta, Stefano \
Palma, Chiara
