# Link_Prediction_via_Node_Pair_Ranking

In this project, we built a graph embedding model that extracts precise node embeddings without using other node features.
We used the idea that ‘Positive node pairs have a higher dot product between their embeddings compared to negative node pairs’

For this project, we utilized the Cora dataset. Cora dataset consists of a citation network of scientific publications. Each publication (node) is connected by edges (citations) to other publications. The nodes are also labeled with classes that represent the topic of the paper.

1. 'BPR_link_pred.ipynb' is the code for our BPR-based model.
2. 'GAT_link_pred.ipynb' is the code for two baseline models.
   - 'GAT' is a static graph attention network.
   - 'GATv2' is a dynamic graph attention network.
3. We used the basic T4 GPU in Colab.
4. For our project, we have studied and referenced this paper.
   - <BPR: Bayesian Personalized Ranking from Implicit Feedback> (2012) https://arxiv.org/abs/1205.2618
5. I worked with two colleagues at KAIST for this project (Hyeonseop Jung and Seokwon Han)
6. This project was a term project for CS471: Graph Machine Learning and Mining at KAIST
