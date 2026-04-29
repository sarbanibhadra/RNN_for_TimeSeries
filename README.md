# RNN_for_TimeSeries
DEEP NEURAL NETWORKS : RNN vs TRANSFORMER FOR TIME SERIES

Recurrent Neural Networks vs Transformers for Time Series Prediction


This work implements and compares two approaches for 
time series forecasting:
* 1. LSTM or GRU using Keras/PyTorch
* 2. Transformer encoder using Keras/PyTorch layers
#
# Learning Objectives:
* Build recurrent neural networks for sequential data
* Use transformer architecture for time series
* Implement or integrate positional encoding
* Compare RNN vs Transformer architectures
* Understand time series preprocessing and evaluation
#
# IMPORTANT: 
* Positional encoding MUST be added to transformer
* Use torch.nn.TransformerEncoder or keras.layers.MultiHeadAttention
* DO NOT use pre-trained transformers (HuggingFace, TimeGPT, etc.)
* Use temporal train/test split (NO shuffling)
