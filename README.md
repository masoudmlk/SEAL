SEAL -- learning from Subgraphs, Embeddings, and Attributes for Link prediction
===============================================================================

About
-----

Code for SEAL (learning from Subgraphs, Embeddings, and Attributes for Link prediction).

Please also download our DGCNN software to the same level as this folder.

To be polished.

in GNN, I assumed gpu number = 4.
change DGCNN_path in GNN.m
parelle in Main and parellel in GNN.m are not compatible. Change it back to GNN-parallel when released.
change liblinear's matlab names

modifies the evaluation code of baseline methods, support more strict evaluation (all methods use the same positive and negative testing links to evaluate AUC)


Muhan Zhang, Washington University in St. Louis
2/10/2018
