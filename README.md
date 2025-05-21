# DA6401_A3

Wandb Report link:

Project Description:
This project aims to build a transliteration system that converts text from one script to another while preserving its phonetic structure. The system leverages advanced neural network architectures, including Recurrent Neural Networks (RNNs), Gated Recurrent Units (GRUs), and Long Short-Term Memory networks (LSTMs). Using encoder-decoder sequence-to-sequence (Seq2Seq) models, the project explores both the conventional approach and enhanced versions incorporating attention mechanisms to improve accuracy. By comparing these different models, the project seeks to identify the most effective method for transliterating text between various languages from the Dakshina Dataset.


Files info
DL_assignment3.ipynb - The main ipynb file containing the source code along with wandb sweeps for hyperparameter tuning
train.py - Python file to train and run the code
prediction_vanilla.csv - Predicted data of the test set without attention
attention_predictions.csv - Predictions of the test set with Attention

Dependencies
python
numpy
wandb
torch
matplotlib
pandas
