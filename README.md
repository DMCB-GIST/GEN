# GEN
Gene Embedding based feedforward Neural networks

# Datasets
https://zenodo.org/record/6972738#.YvDMenZBxaQ


## The overview
GEN is a prediction model for cancer drug responses and achieves SOTA performance in cancer drug response tasks. 
GEN uses gene embedding vectors as input data, so it could increase the representative power of genes.

![New_Main_Figure1](https://github.com/DMCB-GIST/GEN/assets/31497898/00ba15d5-4d98-4635-b985-dac0c327f637)

(a) and (b) show the workflows of GEN and a conventional method for predicting cancer drug responses, respectively. The workflows are divided into three main stages: the setup stage, the sample representation stage, and the prediction stage, where S and g respectively denote samples and genes. In the final prediction stage, a drug embedding vector is concatenated with the sample embedding vector, and ${\hat{y}}$ represents the predicted drug response value for the given sample.

## Requirements

pytorch >= 1.8.0

conda install pyg -c pyg

pip install scipy

conda install -c anaconda scikit-learn

conda install hickle



