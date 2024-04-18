# Epileptic-Seizure-classification-using-Machine-and-Deep-Learning.

This is a brief project on Classification of epileptic seizures using Deep learning algorithms such a CNN, LSTM, Ensemble learning of CNN+LSTM and Machine learning algorithms such as Random Forest, Decision tree, ADA boosting, KNN, SVM on EEG data. For more accurate classification, DWT feature extraction is done on the dataset.

In this there are two files:
1. Jeswin Main.ipynb
2. Jeswin Main2.ipynb

The dataset a) EpilepticSeizureRecognition.csv is for - JeswinMain.ipynb
The dataset b) chb01 files are for - JeswinMain2.ipynb

Dataset (a) was taken from kaggle 
Dataset (b) was taken from CHB-MIT Scal EEG database, which are raw EEG data files

In the chb01 dataset (01,02,13,14) are NON SEIZURE
In the chb01 dataset (03,04,15,16) are WITH SEIZURE

So while running JeswinMain2.ipynb categorize files into folders accordingly 
The accuracies while running on raw EEG data are comparatively low but you can increase this by adding more SEIZURE and NON SEIZURE EEG data from CHB-MIT database for the models to learn and classify accurately.
