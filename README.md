# CSDTI: An Interpretable Cross-Attention Network for Drug-Target Interaction Prediction
![二稿模型图_1](https://user-images.githubusercontent.com/127482935/224321177-d5980243-1260-47b8-9b7f-d493b9790006.png)
Overview
The system mainly consists of embedding module, representation learning module and interaction module. In the representation learning module, the GNN-based global aggregator and the multi-scale 1D convolution-based protein encoder learn the deep representations of drugs and proteins, respectively, and the interaction module learns the substructure interaction process of drug-target pairs. Finally, the deep representations of the drug-target pairs and the interaction features between them are input to the output module to obtain the prediction results.
