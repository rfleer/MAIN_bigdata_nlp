# MAIN_bigdata_nlp
Final Project for CAS MAIN fall semester 2023, moduls big data and text analytics.

## Data
Data was downloaded from https://www.kaggle.com/datasets/rmisra/news-headlines-dataset-for-sarcasm-detection and saved in directory "../data".

## Jupyter notebooks
1_Main: contains the main code and ouput including data cleaning, preprocessing, model estimations including optuna tuing and misclassification analysis

2_Bert_outputonly: Only displays the outputs from Bert model estimation. Does not run on its own. Reason: the "1_Main" jupyter notebook contains error messages as bert output, as for some unknown reason the code stoped working.

3_Simpler_model: this script is based on https://www.kaggle.com/code/ashfakyeafi/sarcasm-detection and shows data processing and modelling with "nicer" learning curves, at the cost of lower accuracy.

4_Data_Augmentation: in this script, some of the models were re-trained using augmented text data

## Main sources for models:
https://www.kaggle.com/code/madz2000/sarcasm-detection-with-glove-word2vec-83-accuracy<br />
https://www.kaggle.com/code/eisgandar/sarcastic-headlines-detector-lstm<br />
https://www.kaggle.com/code/sahasourav17/sarcasm-detection-with-rnn-ensemble-svm-lr-nb<br />
https://www.kaggle.com/code/ashfakyeafi/sarcasm-detection<br />
https://colab.research.google.com/drive/1-QVZbgfd8vB0cRyZRU7pjnXk6d8Jq_zA#scrollTo=XMP7r5cUV6-B<br />
https://colab.research.google.com/drive/19BCYMuIxoOZ8cdmYtLOWLUZNQ2bs9_fm<br />
https://colab.research.google.com/drive/1yI2EiIqzZmXNzhQDgJqlKadoG1jjAXDm<br />
https://medium.com/optuna/using-optuna-to-optimize-tensorflow-hyperparameters-57b6d4d316a2<br />
https://www.analyticsvidhya.com/blog/2022/01/multi-label-text-classification-using-transfer-learning-powered-by-optuna/<br />
