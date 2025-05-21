# DA6401_A3

Wandb Report link:

https://wandb.ai/ma23m018-indian-institute-of-technology-madras/DA6401_A3/reports/DA6401-Assignment-3--VmlldzoxMjg2NTMxMQ

Project Description:

This project aims to build a transliteration system that converts text from one script to another while preserving its phonetic structure. The system leverages advanced neural network architectures, including Recurrent Neural Networks (RNNs), Gated Recurrent Units (GRUs), and Long Short-Term Memory networks (LSTMs). Using encoder-decoder sequence-to-sequence (Seq2Seq) models, the project explores both the conventional approach and enhanced versions incorporating attention mechanisms to improve accuracy. By comparing these different models, the project seeks to identify the most effective method for transliterating text between various languages from the Dakshina Dataset.


Files info:

1. DL_assignment3.ipynb - The main ipynb file containing the source code along with wandb sweeps for hyperparameter tuning
2. train.py - Python file to train and run the code
3. prediction_vanilla.csv - Predicted data of the test set without attention
4. predictions_attention.csv - Predictions of the test set with Attention

Dependencies:

1. python
2. numpy
3. wandb
4. torch
5. matplotlib
6. pandas

Summary:
1. Best validation accuracy without attention: 40.112 %
2. Validation loss without attention: 0.455
3. Test accuracy without attention: 37.59%
4. Test loss: 0.582
5. Best validation accuracy with attention: 47.314 %
6. Validation loss with attention: 0.407
7. Test accuracy with attention:  41.113 %
8. Test loss:  0.612
