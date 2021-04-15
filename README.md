# LSTM_Last.fm
This repository contains notebooks supporting a study on Sequence Aware Recommender System and the importance of the order within the user hsitory.
The dataset is built from Last.fm dataset (data are organized in sequences of length 20, which are the splitted in two equal parts (10,10): first part will be used as input for training or inference, the second part as label for calculating metrics)

## LSTM notebooks
This directory contains the notebooks coding LSTM models (a seq2one and a seq2seq models)
- "target_ten_lastFM_1k_LSTM_Embeddings_multilabel_session_dataset_filtered_item.ipynb" for LSTM Seq2Seq model
- "target_one_lastFM_1k_LSTM_Embeddings_multilabel_session_dataset_filtered_item.ipynb" for LSTM Seq2Seq model

## RS assement
Contains a notebooks gathering many common recommender used as baseline and comparison
- "RS_assessement.ipynb" for common Recommender systems used as reference

## Dataset
Contains the dataset used (one file for train, one file for test)
