EEC174B - Applied Machine Learning

## **Brain Machine Interface**

**LSTM and CNN folder**: contains the training and testing on the public dataset from 52 subjects. Go to LSTM_CNN_4channels.ipynb to see the general flow of the running processes.

**EEG Model folder**: contains the training and testing on the public dataset from 52 subjects.

**hardware_data folder**: contains 50 (25 trials per class) trials of hardware data from 2 subjects. 

**Hardware_Model.ipynb**: contains the testing and training on the hardware data collected from 2 subjects using the EEGNet model.

## Motor Movement Detection Using 4-64 Channels

This repository contains three different Machine Learning Models used to analyze the differences between a varying number of channels according to the international 10-10 system. The analysis was done on a pre-existing public dataset. The best performing model is selected and underwent an inferencing process on a new set of data collected from 2 subjects using OpenBCI EEG signal detection kit. This new dataset was collected while a subject was performing left and right hand movements.

## Dataset

### **1. Public Dataset**
A publicly available dataset collected from 52 subjects containing EMG and EEG signal recordings during various motor imagery movements. The dataset can be found here: http://gigadb.org/dataset/100295

### **2. Private Dataset**
A dataset collected from two of our team members containing EEG signal recordings during left and right hand movements. The data were sampled at 800Hz using OpenBCI GUI Ganglion board and its associated software.
