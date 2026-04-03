# PROTEIN-PROTEIN-INTERACTION-PREDICTION-USING-MACHINE-LEARNING

Protein-Protein Interactions (PPIs) are a central part of almost all biological mechanisms; however, high-throughput experimental characterization ofPPIs remain labor and time-intensive. We introduce a project attempting to build a deep learning model based on sequence data alone that predict PPIs. This publication describes a strategy using a labeled PPI data set (Kaggle) to train a dual input Bidirectional Long Short-Term Memory (BiLSTM) network. In the proposed approach each sequence is encoded independently before the representations are combined and the model attempts to classify interactions as binary. Initial results indicate that the BiLSTM framework can capture long-range dependencies within protein sequences. Techniques for dealing with potential problems such as class imbalance and ability to generalize to new protein pairs are explored. The ultimate goal of this project is to create an accurate, low cost method for PPI prediction. Further work planned includes the use of protein language models embeddings.


DATASET: https://www.kaggle.com/datasets/spandansureja/ppi-dataset
