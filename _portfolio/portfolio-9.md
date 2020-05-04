---
title: "Exploring weak-ties in incomplete network datasets using Graph Convolutional Networks
excerpt: "We look into the robustness and the utility of weak-ties in with the use of graph convolutional neural networks. 1<br/><img src='/images/500x300.png'>"
collection: portfolio
---

This paper explores the value of weak-ties in classifying academic literature with the use of graph convolutional neural networks. Our experiments look at the results of treating weak-ties as if they were strong-ties to determine if that assumption improves performance. This is done by applying the methodological framework of the Simplified Graph Convolutional Neural Network (SGC) to two academic publication datasets: Cora and Citeseer.  We also examine how node removal affects prediction accuracy by selecting nodes according to different centrality measures.  These experiments provide insight for which nodes are most important for the performance of SGC.
 When removal is based on a more localized selection of nodes, augmenting the network with both strong-ties and weak-ties provides a benefit, indicating that SGC successfully leverages local information of network nodes. 