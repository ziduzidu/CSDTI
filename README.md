# CSDTI: An Interpretable Cross-Attention Network for Drug-Target Interaction Prediction
![二稿模型图_1](https://user-images.githubusercontent.com/127482935/224321177-d5980243-1260-47b8-9b7f-d493b9790006.png)

## Overview
The system mainly consists of embedding module, representation learning module and interaction module. In the representation learning module, the GNN-based global aggregator and the multi-scale 1D convolution-based protein encoder learn the deep representations of drugs and proteins, respectively, and the interaction module learns the substructure interaction process of drug-target pairs. Finally, the deep representations of the drug-target pairs and the interaction features between them are input to the output module to obtain the prediction results.

## Environment
    The algorithm mainly uses the following packages:
    opencv_python==4.5.1.48
    torch==1.7.1
    matplotlib==3.1.2
    pandas==1.2.4
    torch_geometric==1.7.0
    CairoSVG==2.3.2
    tqdm==4.51.0
    numpy==1.20.1
    ipython==7.24.1
    scikit_learn==0.24.2
## Train/test CSDTI
* First, run preprocessing.py using

`python preprocessing.py`
Running preprocessing.py convert the raw data into graph format.
