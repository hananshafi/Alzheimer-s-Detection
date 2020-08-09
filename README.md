# Alzheimer-s-Detection

# Introduction
Language variation can act as a proxy that monitors how patients's cognitive functions have been affected (e.g., issues with word finding and impaired reasoning). The machine learning learning models can exploit these language patterns and thus help in diagnosing the patient.

# Dataset
This repository contains code for detecting Alzheimer's patients from linguistic cues. The dataset used is "Dementia Bank dataset" contains audio transcripts of various individuals on "Recall Test"
The dataset can be downloaded from following link:

           https://dementia.talkbank.org/
           
The dataset consists of a total of 3272 sample sentences of normal and alzheimer's patients.
Out of these figures, 1676 are from class 0 and 1596 are from class 1.
(Here 0 signifies normal patient and 1 signifies alzheimer's patient)

The data distribution is given as :

![data](https://github.com/hananshafi/Alzheimer-s-Detection/blob/master/assets/label_dist.png)

# Methodology          
This project involves the performance comparison between 5 deep learning models. Three neural net models (LSTM, BiLSTM, CNN-LSTM) and two transformer based models (BERT & XLNET) are separately trained with same set of data and the performance comparison is done on the basis of test set accuracy, F1 and ROC scores.

1. LSTM

2. BiLSTM

3. CNN-LSTM

4. BERT

5. XLNET

The LSTM, BiLSTM and CNN-LSTM approaches are implemented in NLP-1 notebook. BERT AND XLNET are implemented in NLP-2 notebook.

# Performance Comparison: Accuracy, F1 Score and ROC curves

## 1. LSTM

### Accuracy Metrics
![LSTM](https://github.com/hananshafi/Alzheimer-s-Detection/blob/master/assets/lstm.JPG)

### ROC Curve
![ROC-LSTM](https://github.com/hananshafi/Alzheimer-s-Detection/blob/master/assets/roc_lstm.png)


## 2. Bidirectional LSTM

### Accuracy Metrics
![BiLSTM](https://github.com/hananshafi/Alzheimer-s-Detection/blob/master/assets/bilstm.JPG)

### ROC Curve
![ROC-BILSTM](https://github.com/hananshafi/Alzheimer-s-Detection/blob/master/assets/roc_bilstm.png)

## 3. CNN-LSTM

### Accuracy Metrics
![CNNLSTM](https://github.com/hananshafi/Alzheimer-s-Detection/blob/master/assets/cnn-lstm.JPG)

### ROC Curve
![ROC-CNNLSTM](https://github.com/hananshafi/Alzheimer-s-Detection/blob/master/assets/roc-onv-lstm.png)

## 4. BERT

### Accuracy Metrics
![BERT](https://github.com/hananshafi/Alzheimer-s-Detection/blob/master/assets/bert.JPG)

### ROC Curve
![ROC-BERT](https://github.com/hananshafi/Alzheimer-s-Detection/blob/master/assets/bert_roc.png)

## 5. XLNET

### Accuracy Metrics
![XLNET](https://github.com/hananshafi/Alzheimer-s-Detection/blob/master/assets/xlnet.JPG)

### ROC Curve
![ROC-XLNET](https://github.com/hananshafi/Alzheimer-s-Detection/blob/master/assets/xlnet_auc_roc.png)
